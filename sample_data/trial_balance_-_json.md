# Trial Balance - JSON

#### cURL Request :

```javascript

curl -X POST https://api-staging.bgl360.com.au/fund/trialBalance?fundId=0000000048f240bd0148f28816c80017 --header "Authorization:bearer df2f0e40-606f-4311-8066-590732fd126b"

```

#### Part of the Response Data :

```javascript

{
  "trialBalance": {
    "fundId": "0000000048f240bd0148f28816c80017",
    "start": "2013-01-01T00:00:00Z",
    "end": "2016-01-01T00:00:00Z",
    "data": [
      ...
      {
        "accountClass": "S",
        "accountCode": "50010/ANWKSR00005P",
        "accountType": {
          "label": "Member",
          "minCode": 50000,
          "maxCode": 59999,
          "name": "Member"
        },
        "name": "(Opening Balance) Aedrwdn, uuaanaurK s - Pension (ABP 5)",
        "units": null,
        "debits": 0,
        "credits": 438984.47,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountCode": "50010/ANWKSR00006A",
        "accountType": {
          "label": "Member",
          "minCode": 50000,
          "maxCode": 59999,
          "name": "Member"
        },
        "name": "(Opening Balance) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)",
        "units": null,
        "debits": 0,
        "credits": 2358.46,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountCode": "50010/DEWHY 00001P",
        "accountType": {
          "label": "Member",
          "minCode": 50000,
          "maxCode": 59999,
          "name": "Member"
        },
        "name": "(Opening Balance) drnwArn,  h  JhB rJ - Pension (ABP 1)",
        "units": null,
        "debits": 0,
        "credits": 1980307.18,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      ...
    ]
  }
}


```
