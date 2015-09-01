# Application Status

The Application Status defines what the Application/Client could do based on the status.

The following table illustrates the currently available Application/Client statuses and their role in the System.




<table>
    <tr>
        <th>Method</th>
        <th>URI</th>
    </tr>
    <tr>
        <td>POST</td>
        <td>https://api-staging.bgl360.com.au/oauth/token?grant_type=authorization_code&code=&lt;Auth-Code&gt;&scope=&lt;Scope&gt;&client_id=&lt;API-Client-ID&gt;&client_secret=&lt;API-Client-Secret &gt;</td>
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
        <td>A unique identifier to identify a client that will be using the BGL API.<br><br>See [Obtaining BGL API Credentials](../getting_started/obtaining_bgl_api_credentials.md) on how to obtain Client Id.</td>
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


<table>
    <tr>
        <th>Status</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>Active
        <td>End-user can assign new authorizatiocode and new access token to the application/client.  <br>The application/client can access user data with the access token</td>
    </tr>
    <tr>
        <td>Inactive</td>
        <td>The Application is inactive and cannot access API end points. <br>Displayed and Editable in My Applications.</td>
    </tr>
    <tr>
        <td>Deleted</td>
        <td>The Application is deleted and cannot access API end points. <br>Not Displayed and Not Editable in My Applications.</td>
    </tr>
</table>
