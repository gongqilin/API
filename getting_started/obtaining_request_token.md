# Obtaining Access token ( Step 3/4 )

Once the client application has the [Authorization code](request_for_an_authorization_code.md), then the client application can obtain an Access Token.

The Access Token will contain vital information that will be need to access the BGL API.

In order for the client to obtain an Access Token, the client application should send a request to BGL API as follows.

<table>
    <tr>
        <th>Method</th>
        <th>URI</th>
    </tr>
    <tr>
        <td>POST</td>
        <td>https://api-staging.bgl360.com.au/oauth/token?grant_type=authorization_code&code=&lt;Auth-Code&gt;&scope=&lt;fundList&gt;&client_id=&lt;API-Client-ID&gt;&client_secret=&lt;API-Client-Secret &gt;</td>
    </tr>
</table>

The URL query parameters are as follows.

<table>
    <tr>
        <th>Parameter</th>
        <th>Description</th>
        <th>Required</th>
    </tr>
    <tr>
        <td>grant_type</td>
        <td>The value of this should always be: **authorization_code**</td>
        <td>Mandatory</td>
    </tr>
    <tr>
        <td>code</td>
        <td>The Authorization Code obtained from BGL API</td>
        <td>Mandatory</td>
    </tr>
    <tr>
        <td>client_id</td>
        <td>A unique identifier to identify a client that will be using the BGL API.<br><br>See [Obtaining BGL API Credentials](obtaining_bgl_api_credentials.md) on how to obtain Client Id.</td>
        <td>Mandatory</td>
    </tr>
    <tr>
        <td>client_secret</td>
        <td>The client secret provided by BGL<br><br>See [Obtaining BGL API Credentials](obtaining_bgl_api_credentials.md) on how to obtain Client Secret.</td>
        <td>Mandatory</td>
    </tr>
    <tr>
        <td>scope</td>
        <td>A URL-encoded,space delimitedlist of member permissions your application is requesting on behalf of the user. If you do not specify a scope in your call, we will fall back to using the default member permissions you defined in your application configuration. <br><br>As described by <a href="http://tools.ietf.org/html/rfc6749#section-3.3">Oauth2 Documentation</a></td>
        <td>Optional</td>
    </tr>
</table>

If the request was successful, the client should get a JSON object containing an access token, token type, refresh token, expiration period and scope.

Example **A** of a request with basic authorisation header for the Access Token is as follows.

Basic authorisation Header is  base64 encoded of &lt;API Client Id&gt;:&lt;API Client Secret&gt;

```javascript

curl -X POST https://api-staging.bgl360.com.au/oauth/token?grant_type=authorization_code&code=<Auth-Code>&scope=<Scope> --header "Authorization: Basic xxxxxxxxxx"

```

Example **B** (**Not recommended for production**) of a request  for the Request Token is as follows.

Basic authorisation Header is  base64 encoded of <API Client Id>:<API Client Secret>

```javascript

curl -X POST https://api-staging.bgl360.com.au/oauth/token?grant_type=authorization_code&code=<Auth-Code>&scope=<Scope>&client_id=<API-Client-ID>&client_secret=<API-Client-Secret>

```

An example of a valid response of a Request Token is as follows.

```javascript

{
access_token: "df2f0e40-606f-4311-8066-590732fd126b"
token_type: "bearer"
refresh_token: "c50a429f-9a6d-449d-8d82-4817798fe27b"
expires_in: 581977
scope: "fundList"
}

```

The below table illustrates the content of a valid Request Token

<table>
    <tr>
        <th>Field</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>access_token</td>
        <td>The access token that is mandatory for requesting data from BGL API. This value must be kept secure</td>
    </tr>
    <tr>
        <td>refresh_token</td>
        <td>A token that may be used to obtain new access tokens. Refresh tokens are valid until the user revokes access</td>
    </tr>
    <tr>
        <td>expires_in</td>
        <td>The number of seconds remaining, from the time it was requested, before the token will expire. Currently, all access tokens are issued with a 7 days lifespan</td>
    </tr>
    <tr>
        <td>token_type</td>
        <td>Identifies the type of token returned. At this time, this field will always have the value Bearer</td>
    </tr>
    <tr>
        <td>scope</td>
        <td>The scope of this access token - what data could be accessed</td>
    </tr>
</table>

There may be instances where the request for the Request Token may fail.  The below table illustrates the causes of a bad request and the outcome the client sees.

<table>
    <tr>
        <th>Cause</th>
        <th>Description</th>
        <th>Error</th>
        <th>Error Description</th>
    </tr>
    <tr>
        <td>Invalid Authorizatoin Code</td>
        <td>When an invalid or expired Authorization code is passed</td>
        <td>INVALID GRANT</td>
        <td>Invalid authorization code: &lt;passed Authorization Code&gt;</td>
    </tr>
    <tr>
        <td>Invalid Client Id</td>
        <td>When an invalid client id is passed</td>
        <td>UNAUTHORIZED</td>
        <td>No client with requested refkey: &lt;passed invalid client id&gt;</td>
    </tr>
    <tr>
        <td>Invalid Client Secret</td>
        <td>When an invalid client secret is passed</td>
        <td>INVALID_CLIENT</td>
        <td>Bad client credentials</td>
    </tr>
    <tr>
        <td>Invalid Grant Type</td>
        <td>When an invalid grant type is passed</td>
        <td>UNSUPPORTED_GRANT_TYPE</td>
        <td>Unsupported grant type: &lt;passed grant type&gt;</td>
    </tr>
</table>
