# Trial Balance - JSON

#### cURL Request :

```javascript

curl -X POST https://api-staging.bgl360.com.au/fund/trialBalance?fundId=0000000048f240bd0148f28816c80017 --header "Authorization:bearer df2f0e40-606f-4311-8066-590732fd126b"

```

#### Response :

```javascript

{
  "trialBalance": {
    "fundId": "0000000048f240bd0148f28816c80017",
    "start": "2013-01-01T00:00:00Z",
    "end": "2016-01-01T00:00:00Z",
    "data": [
      {
        "accountClass": "N",
        "accountType": {
          "label": "Income",
          "minCode": 20000,
          "maxCode": 29999,
          "name": "Income"
        },
        "name": "Changes in Market Values of Investments",
        "units": null,
        "debits": 4636.61,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "C",
        "accountType": {
          "label": "Income",
          "minCode": 20000,
          "maxCode": 29999,
          "name": "Income"
        },
        "name": "Interest Received",
        "units": 0,
        "debits": 0,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Income",
          "minCode": 20000,
          "maxCode": 29999,
          "name": "Income"
        },
        "name": "Challenge Cash Management Account",
        "units": null,
        "debits": 0,
        "credits": 233000,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "N",
        "accountType": {
          "label": "Allocation",
          "minCode": 48000,
          "maxCode": 49999,
          "name": "Allocation"
        },
        "name": "Income Tax Expense",
        "units": null,
        "debits": 34950,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "N",
        "accountType": {
          "label": "Allocation",
          "minCode": 48000,
          "maxCode": 49999,
          "name": "Allocation"
        },
        "name": "Profit/Loss Allocation Account",
        "units": null,
        "debits": 193413.39,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "C",
        "accountType": {
          "label": "Member",
          "minCode": 50000,
          "maxCode": 59999,
          "name": "Member"
        },
        "name": "Opening Balance",
        "units": 0,
        "debits": 0,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Member",
          "minCode": 50000,
          "maxCode": 59999,
          "name": "Member"
        },
        "name": "(Opening Balance) Aedrwdn, uuaanaurK s - Pension (ABP 1)",
        "units": null,
        "debits": 0,
        "credits": 1454359.64,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Member",
          "minCode": 50000,
          "maxCode": 59999,
          "name": "Member"
        },
        "name": "(Opening Balance) Aedrwdn, uuaanaurK s - Pension (ABP 2)",
        "units": null,
        "debits": 0,
        "credits": 401057.59,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Member",
          "minCode": 50000,
          "maxCode": 59999,
          "name": "Member"
        },
        "name": "(Opening Balance) Aedrwdn, uuaanaurK s - Pension (ABP 3)",
        "units": null,
        "debits": 0,
        "credits": 46038.69,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Member",
          "minCode": 50000,
          "maxCode": 59999,
          "name": "Member"
        },
        "name": "(Opening Balance) Aedrwdn, uuaanaurK s - Pension (ABP 4)",
        "units": null,
        "debits": 0,
        "credits": 29.18,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
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
      {
        "accountClass": "S",
        "accountType": {
          "label": "Member",
          "minCode": 50000,
          "maxCode": 59999,
          "name": "Member"
        },
        "name": "(Opening Balance) drnwArn,  h  JhB rJ - Pension (ABP 2)",
        "units": null,
        "debits": 0,
        "credits": 47605.48,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Member",
          "minCode": 50000,
          "maxCode": 59999,
          "name": "Member"
        },
        "name": "(Opening Balance) drnwArn,  h  JhB rJ - Pension (ABP 3)",
        "units": null,
        "debits": 0,
        "credits": 28.62,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Member",
          "minCode": 50000,
          "maxCode": 59999,
          "name": "Member"
        },
        "name": "(Opening Balance) drnwArn,  h  JhB rJ - Pension (ABP 4)",
        "units": null,
        "debits": 0,
        "credits": 444526.25,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Member",
          "minCode": 50000,
          "maxCode": 59999,
          "name": "Member"
        },
        "name": "(Opening Balance) drnwArn,  h  JhB rJ - Accumulation (Accumulation)",
        "units": null,
        "debits": 0,
        "credits": 2288.92,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "C",
        "accountType": {
          "label": "Member",
          "minCode": 50000,
          "maxCode": 59999,
          "name": "Member"
        },
        "name": "Share of Profit/(Loss)",
        "units": 0,
        "debits": 0,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Member",
          "minCode": 50000,
          "maxCode": 59999,
          "name": "Member"
        },
        "name": "(Share of Profit/(Loss)) Aedrwdn, uuaanaurK s - Pension (ABP 1)",
        "units": null,
        "debits": 16543.15,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Member",
          "minCode": 50000,
          "maxCode": 59999,
          "name": "Member"
        },
        "name": "(Share of Profit/(Loss)) Aedrwdn, uuaanaurK s - Pension (ABP 2)",
        "units": null,
        "debits": 4559.09,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Member",
          "minCode": 50000,
          "maxCode": 59999,
          "name": "Member"
        },
        "name": "(Share of Profit/(Loss)) Aedrwdn, uuaanaurK s - Pension (ABP 3)",
        "units": null,
        "debits": 526.05,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Member",
          "minCode": 50000,
          "maxCode": 59999,
          "name": "Member"
        },
        "name": "(Share of Profit/(Loss)) Aedrwdn, uuaanaurK s - Pension (ABP 5)",
        "units": null,
        "debits": 4991.99,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Member",
          "minCode": 50000,
          "maxCode": 59999,
          "name": "Member"
        },
        "name": "(Share of Profit/(Loss)) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)",
        "units": null,
        "debits": 27.4,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Member",
          "minCode": 50000,
          "maxCode": 59999,
          "name": "Member"
        },
        "name": "(Share of Profit/(Loss)) drnwArn,  h  JhB rJ - Pension (ABP 1)",
        "units": null,
        "debits": 22521.48,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Member",
          "minCode": 50000,
          "maxCode": 59999,
          "name": "Member"
        },
        "name": "(Share of Profit/(Loss)) drnwArn,  h  JhB rJ - Pension (ABP 2)",
        "units": null,
        "debits": 542.49,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Member",
          "minCode": 50000,
          "maxCode": 59999,
          "name": "Member"
        },
        "name": "(Share of Profit/(Loss)) drnwArn,  h  JhB rJ - Pension (ABP 4)",
        "units": null,
        "debits": 5057.74,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Member",
          "minCode": 50000,
          "maxCode": 59999,
          "name": "Member"
        },
        "name": "(Share of Profit/(Loss)) drnwArn,  h  JhB rJ - Accumulation (Accumulation)",
        "units": null,
        "debits": 27.4,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "C",
        "accountType": {
          "label": "Asset - Bank",
          "minCode": 60400,
          "maxCode": 60800,
          "name": "AssetBank"
        },
        "name": "Bank Accounts",
        "units": 0,
        "debits": 0,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Asset - Bank",
          "minCode": 60400,
          "maxCode": 60800,
          "name": "AssetBank"
        },
        "name": "Andrews SF share transactions account",
        "units": null,
        "debits": 25597.51,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Asset - Bank",
          "minCode": 60400,
          "maxCode": 60800,
          "name": "AssetBank"
        },
        "name": "Westpac Business Cash Reserve 16-0105",
        "units": null,
        "debits": 158367.97,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Asset - Bank",
          "minCode": 60400,
          "maxCode": 60800,
          "name": "AssetBank"
        },
        "name": "Westpac Business Flexi 27-0988",
        "units": null,
        "debits": 50484.69,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Asset - Bank",
          "minCode": 60400,
          "maxCode": 60800,
          "name": "AssetBank"
        },
        "name": "NAB Term Deposit 11-566-4704",
        "units": null,
        "debits": 352041.24,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Asset - Bank",
          "minCode": 60400,
          "maxCode": 60800,
          "name": "AssetBank"
        },
        "name": "NAB Term Deposit 11-647-3782",
        "units": null,
        "debits": 257687.68,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Asset - Bank",
          "minCode": 60400,
          "maxCode": 60800,
          "name": "AssetBank"
        },
        "name": "NAB Term Deposit 12-914-8292",
        "units": null,
        "debits": 225000,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Asset - Bank",
          "minCode": 60400,
          "maxCode": 60800,
          "name": "AssetBank"
        },
        "name": "Westpac Term Deposit 164325 (Matures 25/03/15)",
        "units": null,
        "debits": 150000,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Asset - Bank",
          "minCode": 60400,
          "maxCode": 60800,
          "name": "AssetBank"
        },
        "name": "Westpac Term Deposit 170346",
        "units": null,
        "debits": 350000,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "N",
        "accountType": {
          "label": "Asset",
          "minCode": 60000,
          "maxCode": 69999,
          "name": "Asset"
        },
        "name": "Sundry Debtors",
        "units": null,
        "debits": 1528,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "C",
        "accountType": {
          "label": "Investment",
          "minCode": 70000,
          "maxCode": 79999,
          "name": "Investment"
        },
        "name": "Fixed Interest Securities (Australian) - Unitised",
        "units": 0,
        "debits": 0,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Investment",
          "minCode": 70000,
          "maxCode": 79999,
          "name": "Investment"
        },
        "name": "Athena Finance Pty Ltd",
        "units": 1,
        "debits": 100000,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "C",
        "accountType": {
          "label": "Investment",
          "minCode": 70000,
          "maxCode": 79999,
          "name": "Investment"
        },
        "name": "Other Assets",
        "units": 0,
        "debits": 0,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Investment",
          "minCode": 70000,
          "maxCode": 79999,
          "name": "Investment"
        },
        "name": "WPL DRP Residual",
        "units": null,
        "debits": 25.47,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "C",
        "accountType": {
          "label": "Investment",
          "minCode": 70000,
          "maxCode": 79999,
          "name": "Investment"
        },
        "name": "Plant and Equipment (at written down value) - Unitised",
        "units": 0,
        "debits": 0,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Investment",
          "minCode": 70000,
          "maxCode": 79999,
          "name": "Investment"
        },
        "name": "Bore Pump (Carter Road)",
        "units": 1,
        "debits": 2384.34,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Investment",
          "minCode": 70000,
          "maxCode": 79999,
          "name": "Investment"
        },
        "name": "Pioneer Water Tank (Carter Road)",
        "units": 1,
        "debits": 9467.09,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Investment",
          "minCode": 70000,
          "maxCode": 79999,
          "name": "Investment"
        },
        "name": "Rainwater Tank (Carter Road)",
        "units": 1,
        "debits": 2323.26,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Investment",
          "minCode": 70000,
          "maxCode": 79999,
          "name": "Investment"
        },
        "name": "Shed (Carter Road)",
        "units": 1,
        "debits": 125218,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Investment",
          "minCode": 70000,
          "maxCode": 79999,
          "name": "Investment"
        },
        "name": "Tenant's Tank (Carter Road)",
        "units": 1,
        "debits": 5426.06,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Investment",
          "minCode": 70000,
          "maxCode": 79999,
          "name": "Investment"
        },
        "name": "Water Tank (Carter Road)",
        "units": 1,
        "debits": 7166.7,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "C",
        "accountType": {
          "label": "Investment",
          "minCode": 70000,
          "maxCode": 79999,
          "name": "Investment"
        },
        "name": "Real Estate Properties ( Australian - Residential)",
        "units": 0,
        "debits": 0,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Investment",
          "minCode": 70000,
          "maxCode": 79999,
          "name": "Investment"
        },
        "name": "Lot 4, Carters Road, Margaret River",
        "units": 1,
        "debits": 1600000,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "C",
        "accountType": {
          "label": "Investment",
          "minCode": 70000,
          "maxCode": 79999,
          "name": "Investment"
        },
        "name": "Shares in Listed Companies (Australian)",
        "units": 0,
        "debits": 0,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Investment",
          "minCode": 70000,
          "maxCode": 79999,
          "name": "Investment"
        },
        "name": "Bhp Billiton Limited",
        "units": 4000,
        "debits": 102000,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Investment",
          "minCode": 70000,
          "maxCode": 79999,
          "name": "Investment"
        },
        "name": "Falcon Minerals Limited - Ordinary Fully Paid",
        "units": 30000,
        "debits": 330,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Investment",
          "minCode": 70000,
          "maxCode": 79999,
          "name": "Investment"
        },
        "name": "Goconnect Limited - Ordinary Fully Paid",
        "units": 250000,
        "debits": 1750,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Investment",
          "minCode": 70000,
          "maxCode": 79999,
          "name": "Investment"
        },
        "name": "Iron Ore Holdings Limited - Ordinary Fully Paid",
        "units": 15000,
        "debits": 10500,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Investment",
          "minCode": 70000,
          "maxCode": 79999,
          "name": "Investment"
        },
        "name": "Lynas Corporation Limited - Ordinary Fully Paid",
        "units": 35578,
        "debits": 1351.96,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Investment",
          "minCode": 70000,
          "maxCode": 79999,
          "name": "Investment"
        },
        "name": "Newcrest Mining Limited",
        "units": 2000,
        "debits": 23680,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Investment",
          "minCode": 70000,
          "maxCode": 79999,
          "name": "Investment"
        },
        "name": "Norwest Energy Nl - Ordinary Fully Paid",
        "units": 200000,
        "debits": 1000,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Investment",
          "minCode": 70000,
          "maxCode": 79999,
          "name": "Investment"
        },
        "name": "Otto Energy Limited - Ordinary Fully Paid",
        "units": 150000,
        "debits": 10200,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Investment",
          "minCode": 70000,
          "maxCode": 79999,
          "name": "Investment"
        },
        "name": "OZ Minerals Ltd",
        "units": 4000,
        "debits": 15320,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Investment",
          "minCode": 70000,
          "maxCode": 79999,
          "name": "Investment"
        },
        "name": "Platinum Australia Limited - Ordinary Fully Paid",
        "units": 19000,
        "debits": 1273,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Investment",
          "minCode": 70000,
          "maxCode": 79999,
          "name": "Investment"
        },
        "name": "Rio Tinto Limited",
        "units": 800,
        "debits": 40960,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Investment",
          "minCode": 70000,
          "maxCode": 79999,
          "name": "Investment"
        },
        "name": "Regis Resources Limited - Ordinary Fully Paid",
        "units": 10000,
        "debits": 13500,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Investment",
          "minCode": 70000,
          "maxCode": 79999,
          "name": "Investment"
        },
        "name": "Regis Resources Limited - Option Expiring 31-Jan-2014",
        "units": 8000,
        "debits": 18000,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Investment",
          "minCode": 70000,
          "maxCode": 79999,
          "name": "Investment"
        },
        "name": "Tap Oil Limited",
        "units": 10000,
        "debits": 3400,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Investment",
          "minCode": 70000,
          "maxCode": 79999,
          "name": "Investment"
        },
        "name": "Telstra Corporation Ltd",
        "units": 47000,
        "debits": 298450,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Investment",
          "minCode": 70000,
          "maxCode": 79999,
          "name": "Investment"
        },
        "name": "Uranex Limited - Ordinary Fully Paid",
        "units": 15000,
        "debits": 2400,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Investment",
          "minCode": 70000,
          "maxCode": 79999,
          "name": "Investment"
        },
        "name": "Viralytics Limited - Ordinary Fully Paid",
        "units": 15650,
        "debits": 12207,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Investment",
          "minCode": 70000,
          "maxCode": 79999,
          "name": "Investment"
        },
        "name": "West African Resources Limited - Ordinary Fully Paid",
        "units": 40000,
        "debits": 3400,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Investment",
          "minCode": 70000,
          "maxCode": 79999,
          "name": "Investment"
        },
        "name": "Westpac Banking Corporation - Convertible Preference Shares",
        "units": 1000,
        "debits": 101500,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Investment",
          "minCode": 70000,
          "maxCode": 79999,
          "name": "Investment"
        },
        "name": "Woodside Petroleum",
        "units": 6251,
        "debits": 210096.11,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "C",
        "accountType": {
          "label": "Investment",
          "minCode": 70000,
          "maxCode": 79999,
          "name": "Investment"
        },
        "name": "Units in Unlisted Unit Trusts (Australian)",
        "units": 0,
        "debits": 0,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "S",
        "accountType": {
          "label": "Investment",
          "minCode": 70000,
          "maxCode": 79999,
          "name": "Investment"
        },
        "name": "Sea Pines Investment Trust",
        "units": 500000,
        "debits": 495100,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "N",
        "accountType": {
          "label": "Liability",
          "minCode": 80000,
          "maxCode": 89999,
          "name": "Liability"
        },
        "name": "GST Payable/Refundable",
        "units": null,
        "debits": 511.61,
        "credits": 0,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      },
      {
        "accountClass": "N",
        "accountType": {
          "label": "Liability",
          "minCode": 80000,
          "maxCode": 89999,
          "name": "Liability"
        },
        "name": "Income Tax Payable/Refundable",
        "units": null,
        "debits": 0,
        "credits": 26860,
        "unitsPrev": 0,
        "debitsPrev": 0,
        "creditsPrev": 0,
        "balancePrev": 0
      }
    ]
  }
}


```
