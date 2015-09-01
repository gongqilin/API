# Edit Application

The Edit Application Details page allows you to make changes to the application information you have previously entered.  

<table>
    <tr>
        <th>Field</th>
        <th>Description</th>
        <th>Required</th>
    </tr>
    <tr>
        <td>Name</td>
        <td>The API Application/Client Name.</td>
        <td>Yes</td>
    </tr>
    <tr>
        <td>Owner</td>
        <td>Username who owns/created the application.  This is a read-only field.</td>
        <td>Yes</td>
    </tr>
    <tr>
        <td>Web Site</td>
        <td>The Web Site URL of the Organization using this Application/Client.  The entered URL should be a valid, well formed URL.</td>
        <td>No</td>
    </tr>
    <tr>
        <td>Logo in Authorization Page</td>
        <td>The Logo that will be displayed in the Authorization Page.  Enter a valid url that points to the Organization Logo.  <br><br>Select 'Preview' to preview the entered logo URL.</td>
        <td>No</td>
    </tr>
    <tr>
        <td>Authorize URL</td>
        <td>This is an auto generated URL that could be used to obtain the Authorization Code. This is a read-only field.  Select the copy button next to this URL to copy this URL to the clip board.  <br><br>Please see Request for Authorization section for more details.  </td>
        <td>No</td>
    </tr>
    <tr>
        <td>Access Token URL</td>
        <td>This is an auto generated URL that could be used to obtain the Access Token Code.  This is a read-only field. Select the copy button next to this URL to copy this URL to the clip board.  <br><br>Please see Obtain Access Token section for more details.  Replace '%3CAUTHCODE%3E' with the actual Authorization code before using this URL.  </td>
        <td>No</td>
    </tr>
    <tr>
        <td>Consumer Key</td>
        <td>This is a read-only field, displaying the unique Client Id.</td>
        <td>Yes</td>
    </tr>
    <tr>
        <td>Conumer Secret</td>
        <td>This is a read-only field.  When the Application/Client is loaded into the Edit Application screen, the Client Secret is displayed in the encrypted format.
        <br><br>Select **Regenerate Secret** to regenerate the Consumer Secret.  Once the Consumer Secret is regenerated it will be displayed in raw format.  This should be copied and safe guarded. When the Consume Secret is regenerated, the user will be displayed a copy button next to the generated secret.  You could select the copy button to copy the Consumer Secret to the clip board.
        <br><br>Once the Application is saved this secret will be encrypted. BGL does not store the raw form and there is no way of retrieving the raw form.  </td>
        <td>Yes</td>
    </tr>
    <tr>
        <td>Redirect URLs</td>
        <td>The URL that will be used to redirect after Authorization.  <br><br>The first URL entered in the list will be taken as the default redirect url (which will be displayed in a different colour in the list).  <br><br>However, if you wish to use any other call back url in the list that you have added, then you will need to provide this in the request for authorization code url.  Please see Request For an Authorization Code for more details.  <br><br>Atleast one Redicrect URL should be added to this field.  You can add upto 05 Redicrect URLs.  Only valid URLs can be entered into this field.</td>
        <td>Yes</td>
    </tr>
    <tr>
        <td>Scope</td>
        <td>The API Application/Client Scope. Please see Application/Client Scopes for more details.  Currently the supported type is 'Developer'.</td>
        <td>Yes</td>
    </tr>
</table>

Select 'Save' to update the API Application/client. The Application will be updated and you will be redirected to the List Application page.

####Success Messages

<table>
    <tr>
        <th>Message</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>Updated &lt;Application Name/Client&gt; Successfully</td>
        <td>If updating the Application/Client was successful.</td>
    </tr>
</table>


####Error Messages

<table>
    <tr>
        <th>Message</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>Application Name cannot be left blank</td>
        <td>If you have not entered a Name for the Application/Client.</td>
    </tr>
    <tr>
        <td>Application Web Site should have a valid URL or should be kept empty</td>
        <td>If you have entered an invalid URL for the Web Site.</td>
    </tr>
    <tr>
        <td>ApplicationApplication Logo should have a valid URL or should be kept empty</td>
        <td>If you have entered an invalid URL for the Application Logo URL.</td>
    </tr>
    <tr>
        <td>At least 1 Redirect URL should exist</td>
        <td>If you have not entered a Redirect URL.</td>
    </tr>
</table>
