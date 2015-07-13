# Request : Chart Accounts

|  |  |
| -- | -- |
| Description | Allows you to retrieve the Chart of Acounts based on a fund id  |
| Sample Request| https://api-uat.bgl360.com.au/fund/chartAccounts |
| Method support | GET, POST|

### Parameters


The following parameters can be added into the http request or set in the Content-Type in the header.

|  |  | |
| :--: | -- | -- |
| fundId | The unique id to obtain chart of accounts. | MANDATORY |
| format=json <br> or <br> .json | This is the default. Will return the data in JSON format. | OPTIONAL |
| format=xml  <br> or <br> .xml | Will return the data in XML format. | OPTIONAL |


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
</root>```

