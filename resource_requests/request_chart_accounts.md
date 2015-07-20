# Request : Chart of Accounts

<table>
    <tr>
        <td>Description</td>
        <td>Allows you to retrieve the Chart of Acounts based on a fund id</td>
    </tr>
    <tr>
        <td>Request URI</td>
        <td>/fund/chartAccounts</td>
    </tr>
    <tr>
        <td>Method</td>
        <td>GET | POST</td>
    </tr>
</table>

### Parameters

The following parameters can be added in the http request.

<table>
    <tr>
        <th>Parameter</th>
        <th>Description</th>
        <th>Required</th>
    </tr>
    <tr>
        <td align="center">fundId</td>
        <td>The unique fund id</td>
        <td  align="center">Mandatory</td>
    </tr>
    <tr>
        <td align="center">format=json <br> or <br> .json</td>
        <td>This is the default. Will return the data in JSON format</td>
        <td  align="center">Optional</td>
    </tr>
    <tr>
        <td align="center">format=xml  <br> or <br> .xml</td>
        <td>Will return the data in XML format</td>
        <td  align="center">Optional</td>
    </tr>
<table>

If the format parameter is not set, the returned result will always be JSON.

### Sample Request and Response



#### JSON

See section - [Chart of Accounts - JSON](../sample_data/char_of_accounts_-_json.md) for sample request and json response.

#### XML

See section [Chart of Accounts - XML](../sample_data/chart_of_accounts_-_xml.md) for sample request and xml response.

#### Error Messages


If the provided fund id is not found in the BGL data, the following error will be returned.

```javascript

{
	"message": "The fund is not found/accessible",
	"errors": ["The fund is not found/accessible"],
	"status": 401
}

```


