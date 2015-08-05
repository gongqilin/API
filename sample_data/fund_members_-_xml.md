# Fund Members - XML

#### cURL Request :

```javascript

curl -X POST https://api-staging.bgl360.com.au/fund/members.xml?fundId=0000000048f240bd0148f28816c80017 --header "Authorization:bearer df2f0e40-606f-4311-8066-590732fd126b"

```

#### Response :


```xml

<root xmlns='http://www.bglcorp.com.au'>
  <Members>
    <Member>
      <FirstName>Rogger</FirstName>
      <LastName>Ross</LastName>
      <Title>Mr</Title>
      <Dob>2015-07-29</Dob>
      <Address>
        <StreetLine1>608</StreetLine1>
        <StreetLine2>Hawthorn Road</StreetLine2>
        <City>Brighton</City>
        <State>VIC</State>
        <Country>Australia</Country>
        <PostCode>25522</PostCode>
      </Address>
      <Email>rogger.ross@reee.com.au</Email>
      <Gender>Male</Gender>
    </Member>
    <Member>
      <FirstName>Margret</FirstName>
      <LastName>Ross</LastName>
      <Title>Mrs</Title>
      <Dob>2015-08-02</Dob>
      <Address>
        <StreetLine1>2005</StreetLine1>
        <StreetLine2>xyz street</StreetLine2>
        <City>Boxhill</City>
        <State>VIC</State>
        <Country>Australia</Country>
        <PostCode>5447</PostCode>
      </Address>
      <Email>margret.ross@reer.com.au</Email>
      <Gender>Female</Gender>
    </Member>
    <Member>
      <FirstName>Tom</FirstName>
      <LastName>Mercy</LastName>
      <Title>Mr</Title>
      <Dob>2015-07-31</Dob>
      <Address>
        <StreetLine1>232</StreetLine1>
        <StreetLine2>abc</StreetLine2>
        <City>Perth</City>
        <State>WA</State>
        <Country>Austrlia</Country>
        <PostCode>7889</PostCode>
      </Address>
      <Email>nyh.eee@dse.com.au</Email>
      <Gender>Nonspecified</Gender>
    </Member>
  </Members>
</root>

```
