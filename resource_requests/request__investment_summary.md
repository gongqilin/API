# Request : Investment Summary

<table>
    <tr>
        <td>Description</td>
        <td>Allows you to retrieve List of Individual Summaries</td>
    </tr>
    <tr>
        <td>Request URI</td>
        <td>https://api-uat.bgl360.com.au/fund/investmentSummary</td>
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
        <td  align="center">Optional</td>
    </tr>
    <tr>
        <td align="center">start</td>
        <td>Start date of Investment.  Expected format : yyyy-mm-dd</td>
        <td  align="center">Optional</td>
    </tr>
    <tr>
        <td align="center">end</td>
        <td>End date of Investment.  Expected Format : yyyy-mm-dd</td>
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

#### cURL Request - JSON

```javascript

curl -X POST https://api-uat.bgl360.com.au/fund/investmentSummary?fundId=0000000048f240bd0148f28816c80017 --header "Authorization:bearer df2f0e40-606f-4311-8066-590732fd126b"

```

#### Response - JSON

```javascript

{
	"investmentSummary": [{
		"fundId": "0000000048f240bd0148f28816c80017",
		"start": "2015-04-30T00:00:00Z",
		"end": "2015-05-01T00:00:00Z",
		"data": [{
			"investmentName": "Andrews SF share transactions account",
			"code": "0040605685885",
			"units": null,
			"mktPrice": 25597.51,
			"cost": 25597.51,
			"mktValueAsPerLedger": 25597.51,
			"currentYearUnRealisedMovement": null,
			"investmentGroup": "Cash/Bank Accounts",
			"aveCost": 25597.51,
			"unitsMarketPrice": 25597.51,
			"unRealisedMovement": null,
			"realisedMovement": null
		},
		{
			"investmentName": "Lynas Corporation Limited - Ordinary Fully Paid",
			"code": "LYC.AX",
			"units": 35578,
			"mktPrice": 0.045,
			"cost": 66492.61,
			"mktValueAsPerLedger": 1601.01,
			"currentYearUnRealisedMovement": -35.58,
			"investmentGroup": "Shares in Listed Companies (Australian)",
			"aveCost": 1.87,
			"unitsMarketPrice": 1601.01,
			"unRealisedMovement": -64891.6000000000000,
			"realisedMovement": 0
		},
		{
			"investmentName": "National Aust. Bank",
			"code": "NAB.AX",
			"units": 0,
			"mktPrice": 36.77,
			"cost": -2.17,
			"mktValueAsPerLedger": 0,
			"currentYearUnRealisedMovement": 0,
			"investmentGroup": "Shares in Listed Companies (Australian)",
			"aveCost": 0,
			"unitsMarketPrice": 0E-13,
			"unRealisedMovement": 2.17,
			"realisedMovement": 0
		},
		{
			"investmentName": "Newcrest Mining Limited",
			"code": "NCM.AX",
			"units": 2000,
			"mktPrice": 14.45,
			"cost": 50195.79,
			"mktValueAsPerLedger": 28900,
			"currentYearUnRealisedMovement": 240,
			"investmentGroup": "Shares in Listed Companies (Australian)",
			"aveCost": 25.1,
			"unitsMarketPrice": 28900.0000000000000,
			"unRealisedMovement": -21295.7900000000000,
			"realisedMovement": 0
		}]
	}
	],
	"total": 84,
	"offset": 0,
	"max": 50
}

```

#### cURL Request - XML

```javascript

curl -X POST https://api-uat.bgl360.com.au/fund/investmentSummary.xml?fundId=0000000048f240bd0148f28816c80017 --header "Authorization:bearer df2f0e40-606f-4311-8066-590732fd126b"

```

#### Response - XML

```xml

<root xmlns='http://www.bglcorp.com.au'>
  <InvestmentSummary>
    <InvestmentSummary>
      <FundId>0000000048f240bd0148f28816c80017</FundId>
      <Start>Thu Apr 30 00:00:00 UTC 2015</Start>
      <End>Fri May 01 00:00:00 UTC 2015</End>
      <Data>
        <Data>
          <InvestmentName>Rainwater Tank (Carter Road)</InvestmentName>
          <Code>MIGRAT04_RAINWATERTA</Code>
          <Units>1</Units>
          <MktPrice>0</MktPrice>
          <Cost>2478.18</Cost>
          <MktValueAsPerLedger>2323.26</MktValueAsPerLedger>
          <CurrentYearUnRealisedMovement>0</CurrentYearUnRealisedMovement>
          <InvestmentGroup>Plant and Equipment (at written down value) - Unitised</InvestmentGroup>
          <AveCost>2478.18</AveCost>
          <UnitsMarketPrice>0</UnitsMarketPrice>
          <UnRealisedMovement>-2478.18</UnRealisedMovement>
          <RealisedMovement>0</RealisedMovement>
        </Data>
        <Data>
          <InvestmentName>Shed (Carter Road)</InvestmentName>
          <Code>MIGRAT04_SHED(CARTER</Code>
          <Units>1</Units>
          <MktPrice>0</MktPrice>
          <Cost>139174.59</Cost>
          <MktValueAsPerLedger>125218</MktValueAsPerLedger>
          <CurrentYearUnRealisedMovement>0</CurrentYearUnRealisedMovement>
          <InvestmentGroup>Plant and Equipment (at written down value) - Unitised</InvestmentGroup>
          <AveCost>139174.59</AveCost>
          <UnitsMarketPrice>0</UnitsMarketPrice>
          <UnRealisedMovement>-139174.59</UnRealisedMovement>
          <RealisedMovement>0</RealisedMovement>
        </Data>
        <Data>
          <InvestmentName>Wmc Limited</InvestmentName>
          <Code>WMC.AX</Code>
          <Units>0</Units>
          <MktPrice>8.2</MktPrice>
          <Cost>-2.17</Cost>
          <MktValueAsPerLedger>0</MktValueAsPerLedger>
          <CurrentYearUnRealisedMovement>0</CurrentYearUnRealisedMovement>
          <InvestmentGroup>Shares in Listed Companies (Australian)</InvestmentGroup>
          <AveCost>0</AveCost>
          <UnitsMarketPrice>0E-13</UnitsMarketPrice>
          <UnRealisedMovement>2.17</UnRealisedMovement>
          <RealisedMovement>0</RealisedMovement>
        </Data>
      </Data>
    </InvestmentSummary>
  </InvestmentSummary>
  <Total>84</Total>
  <Offset>0</Offset>
  <Max>50</Max>
</root>

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
	"message": "Failed to call investmentSummary",
	"errors": ["The Start or End Dates are invalid"],
	"status": 400
}

```

If only one date is present, the following error will be returned.

```javascript

{
	"message": "Failed to call investmentSummary",
	"errors": ["The Start & End Dates are invalid"],
	"status": 400
}

```

If end date is greater than the start date, the following error will be returned.

```javascript

{
	"message": "Failed to call investmentSummary",
	"errors": ["The Start & End Dates are invalid"],
	"status": 400
}

```

