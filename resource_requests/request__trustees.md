# Request : Trustees List

<table>
    <tr>
        <td>Description</td>
        <td>Allows you to retrieve List of Individual Trustees and their details</td>
    </tr>
    <tr>
        <td>Request URI</td>
        <td>https://api-uat.bgl360.com.au/fund/trustees</td>
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

{
	"fundTrustees": [{
		"fundId": "0000000048f240bd0148f28816c80017",
		"relationships": [{
			"entityRole": "Trustee",
			"detail": {
				"name": "drnwArn,  h  JhB rJ",
				"ABN": null,
				"phone": null,
				"firm": "bgltestapi1",
				"contact": {
					"firstName": " h  JhB rJ",
					"lastName": "drnwArn",
					"isUser": false,
					"title": "Mr"
				}
			}
		},
		{
			"entityRole": "Trustee",
			"detail": {
				"name": "Aedrwdn, uuaanaurK s",
				"ABN": null,
				"phone": null,
				"firm": "bgltestapi1",
				"contact": {
					"firstName": "uuaanaurK s",
					"lastName": "Aedrwdn",
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
				"name": "lllulMl,  aiair Gii",
				"ABN": null,
				"phone": null,
				"firm": "bgltestapi1",
				"contact": {
					"firstName": " aiair Gii",
					"lastName": "lllulMl",
					"isUser": false,
					"title": "Mr"
				}
			}
		},
		{
			"entityRole": "Trustee",
			"detail": {
				"name": "lalaaMrauul--CMla, bttitait",
				"ABN": null,
				"phone": null,
				"firm": "bgltestapi1",
				"contact": {
					"firstName": "bttitait",
					"lastName": "lalaaMrauul--CMla",
					"isUser": false,
					"title": "Mrs"
				}
			}
		}]
	}]
}

```

#### XML

```

<root xmlns='http://www.bglcorp.com.au'>
  <FundTrustees>
    <FundTrustee>
      <FundId>0000000048f240bd0148f28816c80017</FundId>
      <Relationships>
        <Relationship>
          <EntityRole>Trustee</EntityRole>
          <Detail>
            <Name>drnwArn,  h  JhB rJ</Name>
            <ABN />
            <Phone />
            <Firm>bgltestapi1</Firm>
            <Contact>
              <FirstName> h  JhB rJ</FirstName>
              <LastName>drnwArn</LastName>
              <IsUser>false</IsUser>
              <Title>Mr</Title>
            </Contact>
          </Detail>
        </Relationship>
        <Relationship>
          <EntityRole>Trustee</EntityRole>
          <Detail>
            <Name>Aedrwdn, uuaanaurK s</Name>
            <ABN />
            <Phone />
            <Firm>bgltestapi1</Firm>
            <Contact>
              <FirstName>uuaanaurK s</FirstName>
              <LastName>Aedrwdn</LastName>
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
            <Name>lllulMl,  aiair Gii</Name>
            <ABN />
            <Phone />
            <Firm>bgltestapi1</Firm>
            <Contact>
              <FirstName> aiair Gii</FirstName>
              <LastName>lllulMl</LastName>
              <IsUser>false</IsUser>
              <Title>Mr</Title>
            </Contact>
          </Detail>
        </Relationship>
        <Relationship>
          <EntityRole>Trustee</EntityRole>
          <Detail>
            <Name>lalaaMrauul--CMla, bttitait</Name>
            <ABN />
            <Phone />
            <Firm>bgltestapi1</Firm>
            <Contact>
              <FirstName>bttitait</FirstName>
              <LastName>lalaaMrauul--CMla</LastName>
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
