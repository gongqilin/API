# Request : Fund Detail

<table>
    <tr>
        <td>Description</td>
        <td>Allows you to retrieve the fund details based on a Fund Id</td>
    </tr>
    <tr>
        <td>Request URI</td>
        <td>/fund/detail</td>
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

See section - [Fund Detail - JSON](../sample_data/fund_detail_-_json.md) for sample request and json response.

#### XML

See section [Fund Detail - XML](../sample_data/fund_detail_-_xml.md) for sample request and xml response.


If the url does not contain the fundId parameter, the BGL API will return the following error.

#### Error Messages

```javascript

{
	"message": "Failed to call detail",
	"errors": ["Fund Id is required"],
	"status": 400
}

```

If the provided fund id is not found in the BGL data, the following error will be returned.

```javascript

{
	"message": "The fund is not found/accessible",
	"errors": ["The fund is not found/accessible"],
	"status": 401
}

```




