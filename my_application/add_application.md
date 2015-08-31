# Add Application

Select **Add Application** in the Application List page, and the user will be redirected to the 'Setup New Application' Page.

Following are the details that needs to be added to create an API Application/Client.

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
        <td>Type</td>
        <td>The API Application/Client Type. Please see Application/Client Types for more details.  Currently the supported type is 'Developer'.</td>
        <td>Yes</td>
    </tr>
    <tr>
        <td>Redirect URLs</td>
        <td>The URL that will be used to redirect after Authorization.  The first URL entered in the list will be taken as the default redirect url (which will be displayed in a different colour in the list).  If you wish to use any other call back url in the list that you have added, then you will need to provide this in the request for authorization code url.  Please see Request For an Authorization Code for more details.  Atleast one Redicrect URL should be added to this field.  You can add upto 05 Redicrect URLs.  Only valid URLs can be entered into this field.</td>
        <td>Yes</td>
    </tr>
    <tr>
        <td>Scope</td>
        <td>The API Application/Client Scope. Please see Application/Client Scopes for more details.  Currently the supported type is 'Developer'.</td>
        <td>Yes</td>
    </tr>
</table>

Once you have entered the necessary information, ensure you have read and agreed to the the Terms and Conditions.

Select 'Save' to add the API Application/client. The Application will be added and you will be redirected to the Edit Application Details page.

The **Close** button will discard any information you have added and take the user to the Application List page.


####Success Messages

<table>
    <tr>
        <th>Message</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>Saved &lt;Application Name/Client&gt; Successfully</td>
        <td>If adding the Application/Client was successful.</td>
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
        <td>At least 1 Redirect URL should exist</td>
        <td>If you have not entered a Redirect URL.</td>
    </tr>
</table>
