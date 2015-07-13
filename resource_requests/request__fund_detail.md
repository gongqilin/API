# Request : Fund Detail


|  |  |
| -- | -- |
| Description | Allows you to retrieve details based on a Fund Id  |
| Sample Request| https://api-uat.bgl360.com.au/fund/detail |
| Method support | GET, POST|

### Parameters


The following parameters can be added into the http request or set in the Content-Type in the header.

|  |  | |
| :--: | -- | -- |
| fundId | The unique id to obtain the fund details. | MANDATORY |
| format=json <br> or <br> .json | This is the default. Will return the data in JSON format. | OPTIONAL |
| format=xml  <br> or <br> .xml| Will return the data in XML format. | OPTIONAL |

If the format parameter is not set, the returned result will always be JSON.

### Sample Response

#### JSON

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


#### XML


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




