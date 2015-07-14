# Making requests for data ( Step 4/4 )

In order for the client to make a request for the data, the client needs to have a valid access token.  Once the client has a valid access token (see [Obtaining Access Token](obtaining_request_token.md)), the client could use the below URI to make the request for data.

<table>
    <tr>
        <th>Method</th>
        <th>URI</th>
    </tr>
    <tr>
        <td>POST | GET</td>
        <td>https://api-staging.bgl360.com.au/fund/list</td>
    </tr>
</table>

The above URI will return the list of all available funds.  There are different variations in retrieving data.  This will be explained in detail in the [next section](../resource_requests/README.md).

However, the client application needs to pass in the access token and token type as header information in the request, as per the following table:

<table>
    <tr>
        <th>Header variable name</th>
        <th>Value</th>
        <th>Example</th>
    </tr>
    <tr>
        <td>Authorization</td>
        <td>&lt;token_type&gt; &lt;access_token&gt;</td>
        <td>bearer df2f0e40-606f-4311-8066-590732fd126b</td>
    </tr>
</table>

By any mean if the client application passes an invalid access token or an invalid token type, the BGL API will provide an error, which is illustrated in the below table.

<table>
    <tr>
        <th>Cause</th>
        <th>Description</th>
        <th>Error</th>
        <th>Error Description</th>
    </tr>
    <tr>
        <td>Invalid Access Token</td>
        <td>When an invalid or expired Access token is set in header</td>
        <td>INVALID_TOKEN</td>
        <td>Invalid access token: &lt;passed access token&gt;</td>
    </tr>
    <tr>
        <td>Invalid Token Type</td>
        <td>When an invalid token type is set in header</td>
        <td>INVALID_TOKEN</td>
        <td>Invalid access token: &lt;passed access token&gt;</td>
    </tr>
</table>

