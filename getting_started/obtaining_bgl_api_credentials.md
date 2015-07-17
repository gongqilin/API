# Obtaining BGL API Credentials ( Step 1/4 )

In order to consume the BGL API, the consuming application needs to register itself with BGL first.  BGL will provide the following information.

<table>
    <tr>
        <th>Subject</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>Client Id</td>
        <td>A unique identifier to identify a client that will be using the BGL API.</td>
    </tr>
    <tr>
        <td>Client Secret</td>
        <td>An app requesting an access token has to know the Client Secret first in order to gain access to the token. The Client Secret will provide authorisation to request the Access Token.  <br><br> <strong>Client Secret must be protected at all cost. If the Client Secret is compromised, a new one must be generated and all authorised apps will have to be updated with the new Client Secret.</strong>
        <br><br> <strong>In any manner, if you feel the Client Secret is compromised, please contact [BGL API Team](mailto:wtan@bglcorp.com.au) immediately. </strong></td>
    </tr>
    <tr>
        <td>Redirect URI</td>
        <td>The URI that will be used for forwarding - based on the authorisation or denial. This will be part of your application that will handle authorisation or access tokens.</td>
    </tr>
    <tr>
        <td>Simple Fund 360 - Demo Account</td>
        <td>This Demo Account can be used to authenticate the client application</td>
    </tr>
</table>

The system from which you can retrieve the above information is currently still work-in-progress.  If you want to request the above information, please send an email to wtan@bglcorp.com.au.
