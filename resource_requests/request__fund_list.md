# Request : Fund List

<table>
    <tr>
        <td>Description</td>
        <td>Allows you to retrieve a list of fund owned by the resource owner (BGL User), which also returns the fund id, which could be used for subsequent API requests</td>
    </tr>
    <tr>
        <td>Request URI</td>
        <td>/fund/list</td>
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

See section - [Fund List - JSON](../sample_data/fund_list_-_json.md) for sample request and json response.

#### XML

See section [Fund List - XML](../sample_data/fund_list_-_xml.md) for sample request and xml response.


