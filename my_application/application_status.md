# Application Status

The Application Status defines what the Application/Client could do based on the status.

The following table illustrates the currently available Application/Client statuses and their role in the System.

<table>
    <tr>
        <th>Status</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>[Active](../getting_started/obtaining_request_token.md)</td>[Obtaining Access Token](obtaining_request_token.md)
          <td>A unique identifier to identify a client application that will be using the BGL API.
        <br><br>See [Obtaining BGL API Credentials](../getting_started/obtaining_bgl_api_credentials.md) on how to obtain Client Id.</td>
        <td>End-user can assign new [[authorization code](../getting_started/obtaining_request_token.md)](../getting_started/request_for_an_authorization_code.md) and new access token to the application/client.  <br>The application/client can access user data with the access token</td>
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
