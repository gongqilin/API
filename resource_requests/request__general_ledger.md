# Request : General Ledger

<table>
    <tr>
        <td>Description</td>
        <td>Allows you to retrieve the General Ledger for a specified fund id</td>
    </tr>
    <tr>
        <td>Request URI</td>
        <td>/fund/generalLedger</td>
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

#### cURL Request - JSON

```javascript

curl -X POST https://api-staging.bgl360.com.au/fund/generalLedger?fundId=0000000048f240bd0148f28816c80017 --header "Authorization:bearer df2f0e40-606f-4311-8066-590732fd126b"

```

#### Response - JSON

```javascript

{
	"generalLedger": {
		"fundId": "0000000048f240bd0148f28816c80017",
		"start": "2015-06-30T14:00:00Z",
		"end": "2016-06-30T13:59:59Z",
		"data": [
		{
			"fundName": null,
			"fromDate": null,
			"toDate": null,
			"year": 2015,
			"id": null,
			"pid": null,
			"entryId": null,
			"accountClass": null,
			"fundId": "",
			"taccountParentName": null,
			"taccountParentCode": "84000",
			"taccountSubCode": "84000",
			"taccountSubName": "GST Payable/Refundable",
			"bsb": "",
			"bankAccNum": "",
			"transactionDate": null,
			"transactionSource": "",
			"createSource": "",
			"processedDate": null,
			"description": "",
			"units": null,
			"amount": 0,
			"balance": 511.61,
			"bankFeedsProvider": null,
			"statementBalance": null,
			"lineType": "total"
		},
		{
			"fundName": null,
			"fromDate": null,
			"toDate": null,
			"year": 2015,
			"id": null,
			"pid": null,
			"entryId": null,
			"accountClass": null,
			"fundId": "",
			"taccountParentName": "Income Tax Payable/Refundable",
			"taccountParentCode": "85000",
			"taccountSubCode": "85000",
			"taccountSubName": "Income Tax Payable/Refundable",
			"bsb": null,
			"bankAccNum": null,
			"transactionDate": "2015-06-30T00:00:00.000+0000",
			"transactionSource": "Opening Balance",
			"createSource": "",
			"processedDate": null,
			"description": "Opening Balance",
			"units": null,
			"amount": null,
			"balance": -26860,
			"bankFeedsProvider": null,
			"statementBalance": null,
			"lineType": "balance"
		},
		{
			"fundName": null,
			"fromDate": null,
			"toDate": null,
			"year": 2015,
			"id": null,
			"pid": null,
			"entryId": null,
			"accountClass": null,
			"fundId": "",
			"taccountParentName": null,
			"taccountParentCode": "85000",
			"taccountSubCode": "85000",
			"taccountSubName": "Income Tax Payable/Refundable",
			"bsb": "",
			"bankAccNum": "",
			"transactionDate": null,
			"transactionSource": "",
			"createSource": "",
			"processedDate": null,
			"description": "",
			"units": null,
			"amount": 0,
			"balance": -26860,
			"bankFeedsProvider": null,
			"statementBalance": null,
			"lineType": "total"
		}]
	}
}

```

#### cURL Request - XML

```javascript

curl -X POST https://api-staging.bgl360.com.au/fund/generalLedger.xml?fundId=0000000048f240bd0148f28816c80017 --header "Authorization:bearer df2f0e40-606f-4311-8066-590732fd126b"

```

#### Response - XML

```xml

<root xmlns='http://www.bglcorp.com.au'>
  <GeneralLedger>
    <FundId>0000000048f240bd0148f28816c80017</FundId>
    <Start>Tue Jun 30 14:00:00 UTC 2015</Start>
    <End>Thu Jun 30 13:59:59 UTC 2016</End>
    <Data>
      <Data>
        <FundName />
        <FromDate />
        <ToDate />
        <Year>2015</Year>
        <Id>2134161</Id>
        <Pid />
        <EntryId>11667226</EntryId>
        <AccountClass>N</AccountClass>
        <FundId></FundId>
        <TaccountParentName>Changes in Market Values of Investments</TaccountParentName>
        <TaccountParentCode>24700</TaccountParentCode>
        <TaccountSubCode>24700</TaccountSubCode>
        <TaccountSubName>Changes in Market Values of Investments</TaccountSubName>
        <Bsb />
        <BankAccNum />
        <TransactionDate>2015-07-11</TransactionDate>
        <TransactionSource>SYSTEM</TransactionSource>
        <CreateSource />
        <ProcessedDate>2015-07-11</ProcessedDate>
        <Description>Revaluation - 10/07/2015 @ $0.1000 (System Price) - 40,000.000000 Units on hand</Description>
        <Units />
        <Amount>-40</Amount>
        <Balance>-40</Balance>
        <BankFeedsProvider />
        <StatementBalance />
        <LineType>trans</LineType>
      </Data>
      <Data>
        <FundName />
        <FromDate />
        <ToDate />
        <Year>2015</Year>
        <Id>2134161</Id>
        <Pid />
        <EntryId>11667244</EntryId>
        <AccountClass>N</AccountClass>
        <FundId></FundId>
        <TaccountParentName>Changes in Market Values of Investments</TaccountParentName>
        <TaccountParentCode>24700</TaccountParentCode>
        <TaccountSubCode>24700</TaccountSubCode>
        <TaccountSubName>Changes in Market Values of Investments</TaccountSubName>
        <Bsb />
        <BankAccNum />
        <TransactionDate>2015-07-11</TransactionDate>
        <TransactionSource>SYSTEM</TransactionSource>
        <CreateSource />
        <ProcessedDate>2015-07-11</ProcessedDate>
        <Description>Revaluation - 10/07/2015 @ $0.7250 (System Price) - 15,650.000000 Units on hand</Description>
        <Units />
        <Amount>-1565</Amount>
        <Balance>-1605</Balance>
        <BankFeedsProvider />
        <StatementBalance />
        <LineType>trans</LineType>
      </Data>
    </Data>
  </GeneralLedger>
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


