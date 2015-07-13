# Obtaining BGL API Credentials

In order to consume BGL API, the consuming application needs to register it self with BGL.  BGL will provide the following information.

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
        <td>An app requesting an access token has to know the Client Secret in order to gain the token. The Client Secret will provide authorization to request the Access Token.  <br><br> <strong>Client Secret must be protected at all costs; if the secret is compromised, a new one must be generated and all authorized apps will have to be updated with the new Client Secret.</strong></td>
    </tr>
    <tr>
        <td>Redirect URI</td>
        <td>The URI that will be used for forwarding - based on the authorization or denial. This will be part of your application that will handle authorization or access tokens.</td>
    </tr>
    <tr>
        <td>Simple Fund 360 - Demo Account</td>
        <td>This could be used to authenticate the client.</td>
    </tr>
</table>

As of now, the system to provide these information are still work-in-progress.  Please do send an email requesting for the above information to wtan@bglcorp.com.au
