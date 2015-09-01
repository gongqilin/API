# Application Status

The Application Status defines what the Application/Client could do based on the status.

The following table illustrates the currently available Application/Client statuses and their role in the System.

<table>
    <tr>
        <th>Status</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>Active</td>
        <td>End-user can assign new [auth-code](request_for_an_authorization_code.md) and new access token to the application/client.  <br>The application/client can access user data with the access token</td>
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
