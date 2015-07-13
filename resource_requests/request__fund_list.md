# Request : Fund List

<table>
    <tr>
        <td>Description</td>
        <td>Allows you to retrieve a list of fund, which also returns the fund id, which could be used for subsequent API requests</td>
    </tr>
    <tr>
        <td>Request URI</td>
        <td>https://api-uat.bgl360.com.au/fund/list</td>
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

"funds": [{
		"fundID": "0000000048f240bd0148f28816c80017",
		"fundCode": "MIGRAT04",
		"fundName": "ANNPSRAOPP4UFENAS4S4TUFUNAPEUFRO",
		"ABN": "95888",
		"firmName": "bgltestapi1",
		"firm": "bgltestapi1",
		"fundEmail": "D@BGLNOTES.COM.AU"
	},
	{
		"fundID": "0000000048f240bd0148f2913f110027",
		"fundCode": "MIGRAT10",
		"fundName": "lroPLPtaL.aaooptoln F  i 2aaru.LroiPS2ounu la ueouto4y",
		"ABN": "5555522",
		"firmName": "bgltestapi1",
		"firm": "bgltestapi1",
		"fundEmail": null
	}]

```
#### XML

```

<root xmlns='http://www.bglcorp.com.au'>
  <Funds>
    <Fund>
      <FundID>0000000048f240bd0148f28816c80017</FundID>
      <FundCode>MIGRAT04</FundCode>
      <FundName>ANNPSRAOPP4UFENAS4S4TUFUNAPEUFRO</FundName>
      <ABN>6558555</ABN>
      <FirmName>bgltestapi1</FirmName>
      <Firm>bgltestapi1</Firm>
      <FundEmail>D@BGLNOTES.COM.AU</FundEmail>
    </Fund>
    <Fund>
      <FundID>0000000048f240bd0148f2913f110027</FundID>
      <FundCode>MIGRAT10</FundCode>
      <FundName>lroPLPtaL.aaooptoln F  i 2aaru.LroiPS2ounu la ueouto4y</FundName>
      <ABN>855544666</ABN>
      <FirmName>bgltestapi1</FirmName>
      <Firm>bgltestapi1</Firm>
      <FundEmail />
    </Fund>
  </Funds>
</root>

```
