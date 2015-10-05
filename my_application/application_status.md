# Application Status

The Application Status defines what the Application/Client can do based on the status.

The following table illustrates the currently available Application/Client statuses and their roles in the System.

<table>
    <tr>
        <th>Status</th>
        <th>Description</th>
    </tr>
    <tr>
        <td id="activeStatus">Active</td>
        <td>1.
End-user can assign a new [authorization code](../getting_started/request_for_an_authorization_code.md) and a new [access token](../getting_started/obtaining_request_token.md) to the application/client.  <br><br>2. The application/client can access data with the access token.<br><br>3. Owner can see and edit the general details of the application/client.</td>
    </tr>
    <tr>
        <td id="inactiveStatus">Inactive</td>
        <td>1.
End-user **CANNOT** assign a new [authorization code](../getting_started/request_for_an_authorization_code.md) and a new [access token](../getting_started/obtaining_request_token.md) to the application/client.  <br><br>2. The application/client can access data with the access token.
<br><br>3. Owner can see and edit the general details of the application/client.</td>
    </tr>
    <tr>
        <td id="deletedStatus">Deleted</td>
        <td>1.
End-user **CANNOT** assign a new [authorization code](../getting_started/request_for_an_authorization_code.md) and a new [access token](../getting_started/obtaining_request_token.md) to the application/client.  <br><br>2. The application/client **CANNOT** access data with the access token.<br><br>3. Owner **CANNOT** see and edit the general details of the application/client.<br><br>4. All existing access token(s) will be removed.</td>
    </tr>
</table>
**To change your application/client status, [please contact us](mailto:wtan@bglcorp.com.au)**.
