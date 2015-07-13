# Request : Chart of Accounts

<table>
    <tr>
        <td>Description</td>
        <td>Allows you to retrieve the Chart of Acounts based on a fund id</td>
    </tr>
    <tr>
        <td>Request URI</td>
        <td>https://api-uat.bgl360.com.au/fund/chartAccounts</td>
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

#### cURL Request - JSON

```

curl -X POST https://api-uat.bgl360.com.au/fund/chartAccounts?fundId=0000000048f240bd0148f28816c80017 --header "Authorization:bearer df2f0e40-606f-4311-8066-590732fd126b"

```

#### Response - JSON

```

{
	"chartAccounts": [{
		"accountClass": "Control",
		"chartAccountType": {
			"label": "Allocation - Member",
			"maxCode": 0,
			"minCode": 0
		},
		"code": "48700",
		"name": "Contributions Tax (Surcharge)"
	},
	{
		"accountClass": "Control",
		"chartAccountType": {
			"label": "Allocation - Member",
			"maxCode": 0,
			"minCode": 0
		},
		"code": "49300",
		"name": "Writeback of Deferred Tax"
	}]
}

```

#### cURL Request - XML

```

curl -X POST https://api-uat.bgl360.com.au/fund/chartAccounts.xml?fundId=0000000048f240bd0148f28816c80017 --header "Authorization:bearer df2f0e40-606f-4311-8066-590732fd126b"

```

#### Response - XML

```

<root xmlns='http://www.bglcorp.com.au'>
  <ChartAccounts>
    <ChartAccount>
      <AccountClass>Control</AccountClass>
      <ChartAccountType>
        <Label>Allocation - Member</Label>
        <MaxCode>0</MaxCode>
        <MinCode>0</MinCode>
      </ChartAccountType>
      <Code>48700</Code>
      <Name>Contributions Tax (Surcharge)</Name>
    </ChartAccount>
    <ChartAccount>
      <AccountClass>Control</AccountClass>
      <ChartAccountType>
        <Label>Allocation - Member</Label>
        <MaxCode>0</MaxCode>
        <MinCode>0</MinCode>
      </ChartAccountType>
      <Code>49300</Code>
      <Name>Writeback of Deferred Tax</Name>
    </ChartAccount>
    <ChartAccount>
      <AccountClass>Control</AccountClass>
      <ChartAccountType>
        <Label>Asset</Label>
        <MaxCode>69999</MaxCode>
        <MinCode>60000</MinCode>
      </ChartAccountType>
      <Code>60100</Code>
      <Name>Amounts owing by Other Persons</Name>
    </ChartAccount>
  </ChartAccounts>
</root>

```

If the provided fund id is not found in BGL data, the following error will be returned.

```

{
	"message": "The fund is not found/accessible",
	"errors": ["The fund is not found/accessible"],
	"status": 401
}

```


