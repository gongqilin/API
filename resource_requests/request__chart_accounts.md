# Request : Chart Accounts

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

The following parameters can be added into the http request or set in the Content-Type in the header.

<table>
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

### Sample Response

#### JSON

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

#### XML

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

