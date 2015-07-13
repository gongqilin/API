# Request : Fund Detail

<table>
    <tr>
        <td>Description</td>
        <td>Allows you to retrieve the fund details based on a Fund Id</td>
    </tr>
    <tr>
        <td>Request URI</td>
        <td>https://api-uat.bgl360.com.au/fund/detail</td>
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

```

curl -X POST https://api-uat.bgl360.com.au/fund/detail?fundId=0000000048f240bd0148f28816c80017 --header "Authorization:bearer df2f0e40-606f-4311-8066-590732fd126b"

```

#### Response - JSON

```

{
	"detail": {
		"activedDate": null,
		"postalAddress": {
			"streetLine1": "L vlLel",
			"streetLine2": "139 Macquarie Street",
			"city": "Dubbo",
			"state": "NEW_SOUTH_WALES",
			"country": "AU",
			"postCode": "2830"
		}
	}
}

```

#### cURL Request - XML

```

curl -X POST https://api-uat.bgl360.com.au/fund/detail.xml?fundId=0000000048f240bd0148f28816c80017 --header "Authorization:bearer df2f0e40-606f-4311-8066-590732fd126b"

```

#### Response - XML

```

<root xmlns='http://www.bglcorp.com.au'>
  <Detail>
    <ActivedDate />
    <PostalAddress>
      <StreetLine1>L vlLel</StreetLine1>
      <StreetLine2>139 Macquarie Street</StreetLine2>
      <City>Dubbo</City>
      <State>NEW_SOUTH_WALES</State>
      <Country>AU</Country>
      <PostCode>2830</PostCode>
    </PostalAddress>
  </Detail>
</root>

```

If the url does not contain the fundId parameter BGL API will notify us with the following error.

```

{
	"message": "Failed to call detail",
	"errors": ["Fund Id is required"],
	"status": 400
}

```

If the provided fund id is not found in BGL data, the following error will be returned.

```

{
	"message": "The fund is not found/accessible",
	"errors": ["The fund is not found/accessible"],
	"status": 401
}

```




