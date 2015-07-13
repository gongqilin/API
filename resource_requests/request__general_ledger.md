# Request : General Ledger

|  |  |
| -- | -- |
| Description | Allows you to retrieve the General Ledger for a specified fund id  |
| Sample Request| https://api-uat.bgl360.com.au/fund/generalLedger |
| Method support | GET, POST|

### Parameters


The following parameters can be added into the http request or set in the Content-Type in the header.

|  |  | |
| :--: | -- | -- |
| fundId | The unique id to obtain general ledger. | MANDATORY |
| format=json <br> or <br> .json | This is the default. Will return the data in JSON format. | OPTIONAL |
| format=xml  <br> or <br> .xml | Will return the data in XML format. | OPTIONAL |
| start | start date of Report.  Expected Format : yyyy-mm-dd | OPTIONAL |
| end | end date of Report.  Expected Format : yyyy-mm-dd | OPTIONAL |


If the format parameter is not set, the returned result will always be JSON.

### Sample Response

#### JSON

```

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

#### XML

```

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


