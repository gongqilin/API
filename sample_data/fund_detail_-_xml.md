# Fund Detail - XML

#### cURL Request :


```javascript

curl -X POST https://api-staging.bgl360.com.au/fund/detail.xml?fundId=0000000048f240bd0148f28816c80017 --header "Authorization:bearer df2f0e40-606f-4311-8066-590732fd126b"

```

#### Response :


```xml
<root xmlns='http://www.bglcorp.com.au'>
  <Detail>
    <ActivedDate>2012-08-14 02:59:30.612</ActivedDate>
    <PostalAddress>
      <StreetLine1>streetLine1</StreetLine1>
      <StreetLine2>streetLine2</StreetLine2>
      <City>city</City>
      <State>state</State>
      <Country>country</Country>
      <PostCode>postCode</PostCode>
    </PostalAddress>
    <Name>name</Name>
    <Abn>abn</Abn>
    <FinancialYearFrom>2015-08-08 00:00:00.000</FinancialYearFrom>
    <FinancialYearEnd>2015-08-14 00:00:00.000</FinancialYearEnd>
    <CreateTime>2012-08-14 02:59:30.614</CreateTime>
    <EstDate>2012-08-08 02:59:30.615</EstDate>
    <DateFormed>2015-08-10 02:59:30.611</DateFormed>
    <WindupDate>2015-08-10 02:59:30.613</WindupDate>
  </Detail>
</root>
```
