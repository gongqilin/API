# Grant Refresh Token

The refresh token grant is performed by exchanging a Refresh Token received during a previous authorization request for an access token  (see [Obtaining Access Token](obtaining_request_token.md)), using the token endpoint.

There are two ways of performing this request

<strong>Request A :</strong> Refresh Token with Authorization Header (Recommended)

 <table>
                <tr>
                    <th>Method</th>
                    <th>URI</th>
                    <th>Header Parameters</th>
                </tr>
                <tr>
                    <td>POST</td>
                    <td>https://api-staging.bgl360.com.au/oauth/token?grant_type=refresh_token&refresh_token=&lt;refresh-token&gt;&client_id=&lt;API-Client-Id&gt;&scope=fundList &gt;</td>
                    <td>Authorization: bearer &lt;Existing Access Token&gt;</td>
                </tr>
            </table>

Following are the request parameters

<table>
    <tr>
        <th>Parameter</th>
        <th>Description</th>
        <th>Required</th>
    </tr>
    <tr>
        <td>grant_type</td>
        <td>The value of this should always be: **refresh_token**</td>
        <td>Mandatory</td>
    </tr>
    <tr>
        <td>refresh_token</td>
        <td>refresh token obtained previously. see [Obtaining Access Token](obtaining_request_token.md) </td>
        <td>Mandatory</td>
    </tr>
    <tr>
        <td>client_id</td>
        <td>A unique identifier to identify a client that will be using the BGL API.<br><br>See [Obtaining BGL API Credentials](obtaining_bgl_api_credentials.md) on how to obtain Client Id.</td>
        <td>Mandatory</td>
    </tr>
    <tr>
        <td>scope</td>
        <td>A URL-encoded,space delimitedlist of member permissions your application is requesting on behalf of the user. If you do not specify a scope in your call, we will fall back to using the default member permissions you defined in your application configuration. <br><br>As described by <a href="http://tools.ietf.org/html/rfc6749#section-3.3">Oauth2 Documentation</a></td>
        <td>Mandatory</td>
    </tr>
</table>

Sample Request

```javascript

curl -X POST https://api-staging.bgl360.com.au/oauth/token?grant_type=refresh_token&refresh_token=<refresh-token>&client_id=<client-id>&scope=<scope> --header "Authorization:bearer <access token>"

```

<strong>Request B :</strong> Refresh Token with Client Secret (Not Recommended)

<table>
                <tr>
                    <th>Method</th>
                    <th>URI</th>
                </tr>
                <tr>
                    <td>POST</td>
                    <td>https://api-staging.bgl360.com.au/oauth/token?grant_type=refresh_token&client_secret=&lt;API-Client-Secret&gt;&refresh_token=&lt;refresh-token&gt;&client_id=&lt;API-Client-Id&gt;&scope=&lt;Scope &gt;</td>
                </tr>
            </table>

Following are the request parameters

<table>
    <tr>
        <th>Parameter</th>
        <th>Description</th>
        <th>Required</th>
    </tr>
    <tr>
        <td>grant_type</td>
        <td>The value of this should always be: **refresh_token**</td>
        <td>Mandatory</td>
    </tr>
    <tr>
        <td>refresh_token</td>
        <td>refresh token obtained previously. see [Obtaining Access Token](obtaining_request_token.md) </td>
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
        <td>Mandatory</td>
    </tr>
</table>

Sample Request

```javascript

curl -X POST https://api-staging.bgl360.com.au/oauth/token?grant_type=refresh_token&refresh_token=<refresh token>&client_id=<client id>&client_secret=<client secret>&scope=<scope>

```

Both of the above requests should return a response similar to example provided below.

```javascript

{
    "access_token": "a3da52c7-4bd2-4d42-a58d-efa64b4de453",
    "token_type": "bearer",
    "refresh_token": "6396c283-47ff-41d2-b887-39bde6af5f1e",
    "expires_in": 43199,
    "scope": "fundList"
}

```

