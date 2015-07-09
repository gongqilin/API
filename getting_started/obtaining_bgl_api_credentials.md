# Obtaining BGL API Credentials

In order to consume BGL API, the consuming application needs to register them self with BGL.  BGL will provide the following information.

| Subject       | Description |
| --            | -- |
| Client Id     | A unique identifier to identify a client that will be using the BGL API |
| Client Secret | An app requesting an access token has to know the Client Secret in order to gain the token. The Client Secret will provide authorization to request the Access Token.  The **Client Secret must be protected at all costs; if the secret is compromised, a new one must be generated and all authorized apps will have to be updated with the new Client Secret**.|
| Redirect URI  | The URL that will be used for forwarding - based on the authorization or denial.  This will be part of your application that will handle authorization or access tokens |
| Simple Fund 360 - Demo Account | This could be used to validate date |


As of now, the system to provide these information are still work-in-progress.  Please do send an email requesting for the above information to wtan@bglcorp.com.au
