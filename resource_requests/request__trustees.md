# Request : Trustees List

<table>
    <tr>
        <td>Description</td>
        <td>Allows you to retrieve a List of Individual Trustees and their details</td>
    </tr>
    <tr>
        <td>Request URI</td>
        <td>/fund/trustees</td>
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

curl -X POST https://api-staging.bgl360.com.au/fund/trustees --header "Authorization:bearer df2f0e40-606f-4311-8066-590732fd126b"

```

#### Response - JSON

```javascript

{
	"fundTrustees": [{
		"fundId": "0000000048f240bd0148f28816c80017",
		"relationships": [{
			"entityRole": "Trustee",
			"detail": {
				"name": "trustee name",
				"ABN": null,
				"phone": null,
				"firm": "bgltestapi1",
				"contact": {
					"firstName": "first name",
					"lastName": "last name",
					"isUser": false,
					"title": "Mr"
				}
			}
		},
		{
			"entityRole": "Trustee",
			"detail": {
				"name": "truestee name2",
				"ABN": null,
				"phone": null,
				"firm": "bgltestapi1",
				"contact": {
					"firstName": "first name",
					"lastName": "last name",
					"isUser": false,
					"title": "Mrs"
				}
			}
		}]
	},
	{
		"fundId": "0000000048f240bd0148f2913f110027",
		"relationships": [{
			"entityRole": "Trustee",
			"detail": {
				"name": "truestee name3",
				"ABN": null,
				"phone": null,
				"firm": "bgltestapi1",
				"contact": {
					"firstName": "first name",
					"lastName": "last name",
					"isUser": false,
					"title": "Mr"
				}
			}
		},
		{
			"entityRole": "Trustee",
			"detail": {
				"name": "truestee name4",
				"ABN": null,
				"phone": null,
				"firm": "bgltestapi1",
				"contact": {
					"firstName": "first name",
					"lastName": "lalaaMrauul--CMla",
					"isUser": false,
					"title": "Mrs"
				}
			}
		}]
	}]
}

```

#### cURL Request - XML

```javascript

curl -X POST https://api-staging.bgl360.com.au/fund/trustees.xml --header "Authorization:bearer df2f0e40-606f-4311-8066-590732fd126b"

```

#### Reponse - XML

```xml

<root xmlns='http://www.bglcorp.com.au'>
  <FundTrustees>
    <FundTrustee>
      <FundId>0000000048f240bd0148f28816c80017</FundId>
      <Relationships>
        <Relationship>
          <EntityRole>Trustee</EntityRole>
          <Detail>
            <Name>truestee name</Name>
            <ABN />
            <Phone />
            <Firm>bgltestapi1</Firm>
            <Contact>
              <FirstName>first name</FirstName>
              <LastName>last name</LastName>
              <IsUser>false</IsUser>
              <Title>Mr</Title>
            </Contact>
          </Detail>
        </Relationship>
        <Relationship>
          <EntityRole>Trustee</EntityRole>
          <Detail>
            <Name>truestee name2</Name>
            <ABN />
            <Phone />
            <Firm>bgltestapi1</Firm>
            <Contact>
              <FirstName>first name</FirstName>
              <LastName>last name</LastName>
              <IsUser>false</IsUser>
              <Title>Mrs</Title>
            </Contact>
          </Detail>
        </Relationship>
      </Relationships>
    </FundTrustee>
    <FundTrustee>
      <FundId>0000000048f240bd0148f2913f110027</FundId>
      <Relationships>
        <Relationship>
          <EntityRole>Trustee</EntityRole>
          <Detail>
            <Name>truestee name3</Name>
            <ABN />
            <Phone />
            <Firm>bgltestapi1</Firm>
            <Contact>
              <FirstName>first name</FirstName>
              <LastName>last name</LastName>
              <IsUser>false</IsUser>
              <Title>Mr</Title>
            </Contact>
          </Detail>
        </Relationship>
        <Relationship>
          <EntityRole>Trustee</EntityRole>
          <Detail>
            <Name>truestee name4</Name>
            <ABN />
            <Phone />
            <Firm>bgltestapi1</Firm>
            <Contact>
              <FirstName>first name</FirstName>
              <LastName>last name</LastName>
              <IsUser>false</IsUser>
              <Title>Mrs</Title>
            </Contact>
          </Detail>
        </Relationship>
      </Relationships>
    </FundTrustee>
  </FundTrustees>
</root>

```
