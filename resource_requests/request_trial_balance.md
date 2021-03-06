# Request : Trial Balance

<table>
    <tr>
        <td>Description</td>
        <td>Allows you to retrieve the Trial Balance for a specified fund id</td>
    </tr>
    <tr>
        <td>Request URI</td>
        <td>/fund/trialBalance</td>
    </tr>
    <tr>
        <td>Method</td>
        <td>GET | POST</td>
    </tr>
</table>

### Prerequisite

In order to obtain data related to Trial Balance, the [access token](../getting_started/obtaining_request_token.md) must be generated by including **audit** in the scope.

If the request is made regardless of adding **audit** to the scope, then BGL API will return **HTTP Status Code - 403 Forbidden** and no data would be present.

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
        <td align="center">start</td>
        <td>Start date of Report.  Expected format : yyyy-mm-dd</td>
        <td  align="center">Optional</td>
    </tr>
    <tr>
        <td align="center">end</td>
        <td>End date of Report.  Expected Format : yyyy-mm-dd</td>
        <td  align="center">Optional</td>
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

See section - [Trial Balance - JSON](../sample_data/trial_balance_-_json.md) for sample request and json response.

#### XML

See section [Trial Balance - XML](../sample_data/trial_balance_-_xml.md) for sample request and xml response.

#### Error Messages

If the fund id is not provided, the following error will be returned.

```javascript

{
  "message": "Failed to call trialBalance",
  "errors": [
    "Fund Id is required"
  ],
  "status": 400
}

```

If the provided fund id is not found in BGL data, the following error will be returned.

```javascript

{
	"message": "The fund is not found/accessible",
	"errors": ["The fund is not found/accessible"],
	"status": 401
}

```

If Start and End Date are not valid dates, the following error will be returned.

```javascript

{
	"message": "Failed to call trialBalance",
	"errors": ["The Start or End Dates are invalid"],
	"status": 400
}

```

If only one date is present, the following error will be returned.

```javascript

{
	"message": "Failed to call trialBalance",
	"errors": ["The Start & End Dates are invalid"],
	"status": 400
}

```

If end date is greater than the start date, the following error will be returned.

```javascript

{
	"message": "Failed to call trialBalance",
	"errors": ["The Start & End Dates are invalid"],
	"status": 400
}

```



