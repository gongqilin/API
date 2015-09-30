# Char of Accounts - JSON

#### cURL Request :

```javascript

curl -X POST https://api-staging.bgl360.com.au/fund/chartAccounts?fundId=0000000048f240bd0148f28816c80017 --header "Authorization:bearer df2f0e40-606f-4311-8066-590732fd126b"

```


#### Part of the Response Data :


```javascript

{
  "chartAccounts": [
        ...
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
    },
    {
      "code": "77600",
      "name": "Dioro Exploration Nl",
      "subChartAccountCode": "DIO.AX",
      "accountClass": "Sub Account",
      "securityId": 848291,
      "securityCode": null,
      "marketType": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "62000",
      "name": "Dioro Exploration Nl",
      "subChartAccountCode": "DIO.AX",
      "accountClass": "Sub Account",
      "securityId": null,
      "securityCode": null,
      "marketType": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "37500",
      "name": "Dioro Exploration Nl",
      "subChartAccountCode": "DIO.AX",
      "accountClass": "Sub Account",
      "securityId": null,
      "securityCode": null,
      "marketType": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "23900",
      "name": "Dioro Exploration Nl",
      "subChartAccountCode": "DIO.AX",
      "accountClass": "Sub Account",
      "securityId": null,
      "securityCode": null,
      "marketType": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    ...

  ]
}

```
