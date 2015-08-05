# Fund Members - JSON

#### cURL Request :

```javascript

curl -X POST https://api-staging.bgl360.com.au/fund/members?fundId=0000000048f240bd0148f28816c80017 --header "Authorization:bearer df2f0e40-606f-4311-8066-590732fd126b"

```

#### Response :


```javascript

{
  "members": [
    {
      "firstName": "Rogger",
      "lastName": "Ross",
      "title": "Mr",
      "dob": "2015-07-29",
      "address": {
        "streetLine1": "608",
        "streetLine2": "Hawthorn Rd",
        "city": "Brighton",
        "state": "VIC",
        "country": "Australia",
        "postCode": "3522"
      },
      "email": "rogger.ross@xdc.com.au",
      "gender": "Male"
    },
    {
      "firstName": "Margret",
      "lastName": "Ross",
      "title": "Mrs",
      "dob": "2015-08-02",
      "address": {
        "streetLine1": "2005",
        "streetLine2": "xyz street",
        "city": "Boxhill",
        "state": "VIC",
        "country": "Australia",
        "postCode": "5447"
      },
      "email": "margret.ross@xsc.com.au",
      "gender": "Female"
    },
    {
      "firstName": "Tom",
      "lastName": "Mercy",
      "title": "Mr",
      "dob": "2015-07-31",
      "address": {
        "streetLine1": "z",
        "streetLine2": "xtt",
        "city": "Perth",
        "state": "WA",
        "country": "Australia",
        "postCode": "7889"
      },
      "email": "nyh.eee@dse.com.au",
      "gender": "Nonspecified"
    }
  ]
}

```
