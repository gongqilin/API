# Obtaining Request token

Once the client has the Authorization code, as explained in the previous section, then the client can obtain a Request Token.

The Request Token will contain vital information that will be need to access the BGL API.

In order for the client to obtain a Request Token, the client should send a request to BGL OAUTH 2.0 Server as follows.

| Request Type | URL Pattern |
| -- | -- |
| POST | https://api-uat.bgl360.com.au/oauth/token?grant_type=authorization_code&code={Auth Code}&scope={fundList}&client_id={API Client ID}&client_secret={API Client Secret} |

The URL query parameters are as follows.

| Parameter | Description | Required |
| -- | -- | :--: |
| grant_type | The value of this should always be: authorization_code | YES |
| code | The Authorization Code obtained from BGL | YES |
| client_id | A unique identifier to identify a client that will be using the BGL API, Provided by BGL | YES |
| client_secret | The client secret provided by BGL at the time of registration | YES |
|scope |A URL-encoded,space delimitedlist of member permissions your application is requesting on behalf of the user.  If you do not specify a scope in your call, we will fall back to using the default member permissions you defined in your application configuration. As described by [Oauth2 Documentation](http://tools.ietf.org/html/rfc6749#section-3.3). | OPTIONAL |


If the request was successful, the client should get a JSON object containing an access token, token type, expiration period and scope.

An example of a valid Request Token is as follows.

```

{
access_token: "df2f0e40-606f-4311-8066-590732fd126b"
token_type: "bearer"
refresh_token: "c50a429f-9a6d-449d-8d82-4817798fe27b"
expires_in: 581977
scope: "fundList"
}

```

The below table illustrates the content of a valid Request Token

| Field | Description |
| -- | -- |
| access_token | The access token that is mandatory for requesting data from BGL API.  This value must be kept secure. |
| refresh_token | A token that may be used to obtain a new access tokens. Refresh tokens are valid until the user revokes access. |
| expires_in | The number of seconds remaining, from the time it was requested, before the token will expire.  Currently, all access tokens are issued with a 7 days lifespan |
| token_type | Identifies the type of token returned. At this time, this field will always have the value Bearer. |
| scope | The scope of this access token - what data could be accessed |


There may be instances where the request for the Request Token may fail.  The below table illustrates the causes of a bad request and the outcome the client sees.

| Cause | Description | Error | Error Description |
| -- | -- | :--: | :--: |
| Invalid Authorizatoin Code | When an invalid or expired Authorization code is passed | INVALID GRANT |Invalid authorization code: {passed Authorization Code} |
| Invalid Client Id | When an invalid client id is passped | UNAUTHORIZED |No client with requested refkey: {passed invalid client id} |
| Invalid Client Secret | When an invalid client secret is passped | INVALID_CLIENT |Bad client credentials |
| Invalid Grant Type | When an invalid grant type is passped | UNSUPPORTED_GRANT_TYPE |Unsupported grant type: {passed grant type} |
