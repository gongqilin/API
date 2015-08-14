# Fund Detail - JSON

#### cURL Request :

```javascript

curl -X POST https://api-staging.bgl360.com.au/fund/detail?fundId=0000000048f240bd0148f28816c80017 --header "Authorization:bearer df2f0e40-606f-4311-8066-590732fd126b"

```

#### Response :

```javascript

{
  "detail": {
    "activedDate": "2012-08-14T02:59:30Z",
    "postalAddress": {
      "streetLine1": "streetLine1",
      "streetLine2": "streetLine2",
      "city": "city",
      "state": "state",
      "country": "country",
      "postCode": "postCode"
    },
    "name": "name",
    "abn": "abn",
    "financialYearFrom": "2015-08-08T00:00:00Z",
    "financialYearEnd": "2015-08-14T00:00:00Z",
    "createTime": "2012-08-14T02:59:30Z",
    "estDate": "2012-08-08T02:59:30Z",
    "dateFormed": "2015-08-10T02:59:30Z",
    "windupDate": "2015-08-10T02:59:30Z"
  }
}

```
