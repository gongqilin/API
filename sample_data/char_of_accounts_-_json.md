# Char of Accounts - JSON

#### cURL Request :

```javascript

curl -X POST https://api-staging.bgl360.com.au/fund/chartAccounts?fundId=0000000048f240bd0148f28816c80017 --header "Authorization:bearer df2f0e40-606f-4311-8066-590732fd126b"

```


#### Part of the Response Data :


```javascript

{
  "chartAccounts": [
     {
      "code": "59500",
      "name": "Self-Insurance Reserve",
      "subChartAccountCode": null,
      "accountClass": "Control",
      "securityId": null,
      "securityCode": null,
      "marketType": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "48500",
      "name": "Income Tax Expense",
      "subChartAccountCode": null,
      "accountClass": "Normal",
      "securityId": null,
      "securityCode": null,
      "marketType": null,
      "chartAccountType": {
        "label": "Allocation",
        "minCode": 48000,
        "maxCode": 49999,
        "name": "Allocation"
      }
    },
    {
      "code": "83000",
      "name": "James Hardie Industries Nv",
      "subChartAccountCode": "JHX.AX",
      "accountClass": "Sub Account",
      "securityId": null,
      "securityCode": null,
      "marketType": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    }
  ]
}

```
