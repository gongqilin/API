# Request for an Authorization Code

An Authorization Code is necessary to obtain an Access Token from BGL OATH 2.0 Server.  Obtaining an Authorization token is an imporantant step, as it provides assuarance to the client that appropriate permission is being granted to access the BGL API.

To request an authorization code, the client must send a GET request to the BGL OATH 2.0 Server in the following manner.

<table>
    <tr>
        <th>Method</th>
        <th>URI</th>
    </tr>
    <tr>
        <td>GET</td>
        <td>https://api-uat.bgl360.com.au/oauth/authorize?response_type=code&client_id=&lt;API-Client-ID&gt;&scope=&lt;fundList&gt;</td>
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
        <td>response_type</td>
        <td>The value of this should always be: code</td>
        <td>Mandatory</td>
    </tr>
    <tr>
        <td>client_id</td>
        <td>A unique identifier to identify a client that will be using the BGL API, Provided by BGL</td>
        <td>Mandatory</td>
    </tr>
    <tr>
        <td>redirect_uri</td>
        <td>The URI your users will be sent back to after authorization.  This value must match one of the defined OAuth 2.0 Redirect URLs in your application configuration. As described in <a href="http://tools.ietf.org/html/rfc6749#section-3.1.2">Oauth2 Documentation</a></td>
        <td>Optional</td>
    </tr>
    <tr>
        <td>state</td>
        <td>An opaque value used by the client to maintain state between the request and callback. The authorization server includes this value when redirecting the user-agent back to the client. The parameter SHOULD be used for preventing cross-site request forgery as described in <a href="http://tools.ietf.org/html/rfc6749#section-10.12">Oauth2 Documentation</a><br><br> Example : state=DCEeFWf45A53sdfKef424</td>
        <td>Optional</td>
    </tr>
    <tr>
        <td>scope</td>
        <td>A URL-encoded,space delimitedlist of member permissions your application is requesting on behalf of the user.  If you do not specify a scope in your call, we will fall back to using the default member permissions you defined in your application configuration. As described by <a href="http://tools.ietf.org/html/rfc6749#section-3.3">Oauth2 Documentation</a></td>
        <td>Optional</td>
    </tr>
</table>

Once the request is processed one of the following will occur.

<ul>
<li>
<p>
If the user has not previously accepted the application's permission request, the grant has expired or been manually revoked by the user, the system will be redirected to API's authorization screen as displayed below.
</p>

<p>![logo](/images/APIAuthorizationScreen.png "API Authorization")</p>


<p>When the user completes the authorization process, the browser is redirected to the URL  provided in the redirect_uri query parameter or default redirect_uri in your API setup, with the authorization code.</p>
</li>
</ul>

<ul>
<li>
<p>
If a valid granted permission exists for the client, the authorization screen is by-passed and the user is immediately redirected to the URL provided in the redirect_uri query parameter, which will contain the authorization code and a state if a state parameter was sent in the original request
</p>
<p>
Example : http://www.client-url.com.au/oauth/authCode?code=LqAx2wO
</p>
</li>
</ul>

For security reasons, the authorization code has a very short lifespan ( about 5 - 10 mins ) and must be used within moments of receiving it.  By any means if the authorization code expires, the client needs to re-request a new authorization token by performing a request to the BGL OATH 2.0 Server, as explained above.

Before the client application accepts the authorization code, the client application should ensure that the value returned in the state parameter matches the state value from the original authorization code request made to BGL with the state parameter. This ensures that you are dealing with the real original user and not a malicious script that has somehow slipped into the middle of your authentication flow.  If the state values do not match, you are likely the victim of a CSRF attack and you should throw an HTTP 401 error code in response.

There may be instances where the request for a Authorization Code may fail.  The below table illustrates the causes of a bad request and the outcome the client sees.

<table>
    <tr>
        <th>Cause</th>
        <th>Description</th>
        <th>Error</th>
        <th>Error Description</th>
    </tr>
    <tr>
        <td>Invalid Client Id</td>
        <td>When an invalid client id is passed as a query parameter</td>
        <td>INVALID CLIENT</td>
        <td>BAD CLIENT CREDENTIALS</td>
    </tr>
    <tr>
        <td>Invalid Response Type</td>
        <td>If response type parameter contains anything apart from "code"</td>
        <td>UNSUPPORTED_RESPONSE_TYPE</td>
        <td>UNSUPPORTED RESPONSE TYPE &lt;The passed invalid code&gt;</td>
    </tr>
    <tr>
        <td>Invalid scope</td>
        <td>The current valid scope are 'fundList','investment','audit' and 'selfwealth'. Appart from these, if the client passes anything else as scope BGL will return an error</td>
        <td>INVALID_SCOPE</td>
        <td>Invalid scope : &lt;The invalid scope passed&gt;</td>
    </tr>
    <tr>
        <td>Invalid redirect URI</td>
        <td>The client should pass the redirect uri that was registered with BGL, as explained in Section - Obtaining BGL API Credentials. If an invalid redirect uri is passed as the redirect_uri parameter, the BGL system will respond with an error</td>
        <td>INVALID GRANT</td>
        <td>INVALID REDIRECT: &lt;passed invalid uri&gt; DOES NOT MATCH ONE OF THE REGISTERED VALUES: [&lt;the url that is registered with the system&gt;]</td>
    </tr>

</table>
