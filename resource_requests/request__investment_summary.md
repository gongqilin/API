# Request : Investment Summary

|  |  |
| -- | -- |
| Description | Allows you to retrieve List of Individual Summaries  |
| Sample Request| https://api-uat.bgl360.com.au/fund/investmentSummary |
| Method support | GET, POST|

### Parameters


The following parameters can be added into the http request or set in the Content-Type in the header.

|  |  | |
| :--: | -- | -- |
| format=json <br> or <br> .json | This is the default. Will return the data in JSON format. | OPTIONAL |
| format=xml  <br> or <br> .xml | Will return the data in XML format. | OPTIONAL |
| fundId | Returns Investments summary based on the fund id. | OPTIONAL |
| start | start date of investment.  Expected Format : yyyy-mm-dd | OPTIONAL |
| end | end date of investment.  Expected Format : yyyy-mm-dd | OPTIONAL |

If the format parameter is not set, the returned result will always be JSON.

### Sample Response

#### JSON


```

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

#### XML

```

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


