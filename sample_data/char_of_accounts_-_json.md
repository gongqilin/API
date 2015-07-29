# Char of Accounts - JSON

#### cURL Request :

```javascript

curl -X POST https://api-staging.bgl360.com.au/fund/chartAccounts?fundId=0000000048f240bd0148f28816c80017 --header "Authorization:bearer df2f0e40-606f-4311-8066-590732fd126b"

```


#### Response :


```javascript

{
  "chartAccounts": [
    {
      "code": "48700",
      "name": "Contributions Tax (Surcharge)",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "49300",
      "name": "Writeback of Deferred Tax",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "60100",
      "name": "Amounts owing by Other Persons",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "61600",
      "name": "Contributions Receivable",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "61800",
      "name": "Distributions Receivable",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "62000",
      "name": "Dividends Receivable",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "65000",
      "name": "Interest Receivable",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "60200",
      "name": "Dividend Reinvestment Plan Balance",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "62501",
      "name": "DRP Residual Value - Westfarmer Ltd",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "65200",
      "name": "Interest Receivable",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "68101",
      "name": "re 11/42 Stud Road Bayswater",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "62502",
      "name": "DRP Residual Value - Westfarmer Ltd",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "68001",
      "name": "Other Debtors",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "60400",
      "name": "Bank Accounts",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset - Bank",
        "minCode": 60400,
        "maxCode": 60800,
        "name": "AssetBank"
      }
    },
    {
      "code": "60800",
      "name": "Term Deposits",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset - Bank",
        "minCode": 60400,
        "maxCode": 60800,
        "name": "AssetBank"
      }
    },
    {
      "code": "33400",
      "name": "Depreciation",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "37500",
      "name": "Investment Expenses",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "41920",
      "name": "Property Expenses - Advertising",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "41930",
      "name": "Property Expenses - Agents Management Fees",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "41940",
      "name": "Property Expenses - Agents Commissions",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "41950",
      "name": "Property Expenses - Cleaning",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "41960",
      "name": "Property Expenses - Council Rates",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "41970",
      "name": "Property Expenses - Garden and Lawn",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "41980",
      "name": "Property Expenses - Insurance Premium",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "41990",
      "name": "Property Expenses - Interest on Deposit Paid",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42000",
      "name": "Property Expenses - Interest on Late Settlement Paid",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42010",
      "name": "Property Expenses - Interest on Loans",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42020",
      "name": "Property Expenses - Land Tax",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42030",
      "name": "Property Expenses - Legal Fees",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42040",
      "name": "Property Expenses - Pest Control",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42050",
      "name": "Property Expenses - Property Capital Improvement",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42060",
      "name": "Property Expenses - Repairs Maintenance",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42070",
      "name": "Property Expenses - Settlement Agent Fees",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42080",
      "name": "Property Expenses - Stamp Duty",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42090",
      "name": "Property Expenses - Stationery, Phone and Postage",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42100",
      "name": "Property Expenses - Strata Levy Fees",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42110",
      "name": "Property Expenses - Sundry Expenses",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42120",
      "name": "Property Expenses - Title Fees",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42130",
      "name": "Property Expenses - Travel",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42140",
      "name": "Property Expenses - Vendor Solicitor's Fees",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42150",
      "name": "Property Expenses - Water Rates",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "33500",
      "name": "Capital Allowance",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42500",
      "name": "Rental Property Expenses",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42501",
      "name": "Viridian - ACT",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42502",
      "name": "Rental Property Expenses",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "39000",
      "name": "Life Insurance Premiums",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39300",
      "name": "Life Insurance Premiums (Non Deductible)",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39400",
      "name": "Income Protection Premiums",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39450",
      "name": "Income Protection Premiums (Non Deductible)",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39500",
      "name": "Total and Permanent Disability Premiums",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39550",
      "name": "Total and Permanent Disability Premiums (Non Deductible)",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39600",
      "name": "Death Cover Premiums",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39650",
      "name": "Death Cover Premiums (Non Deductible)",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "40000",
      "name": "Management Fees",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "40500",
      "name": "Members Expenses",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "41600",
      "name": "Pensions Paid",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "44000",
      "name": "Excess Contributions Tax",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "46000",
      "name": "Benefits Paid/Transfers Out",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "46600",
      "name": "Refund Excess Contributions",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "48100",
      "name": "Division 293 Tax",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "23800",
      "name": "Distributions Received",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "23900",
      "name": "Dividends Received",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "24000",
      "name": "Private dividends and other excessive non-arms length income",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "25000",
      "name": "Interest Received",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "25200",
      "name": "Income in Advance",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "25500",
      "name": "Lease and Hire Income",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "26500",
      "name": "Other Investment Income",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "27000",
      "name": "Partnership Distributions Received",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "27800",
      "name": "Profit/(Loss) on disposal of depreciable assets",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "27850",
      "name": "Profit/(Loss) on disposal of leased depreciable assets",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "28000",
      "name": "Property Income",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "25600",
      "name": "Lease and Hire Income (Non Taxable)",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "26600",
      "name": "Other Income - Non assessable",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "28100",
      "name": "Outgoings received",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "25601",
      "name": "Lease and Hire Income (Non Taxable)",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "26602",
      "name": "Other Income - Non assessable",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "24200",
      "name": "Contributions",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "27500",
      "name": "Proceeds from Insurance Policies",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "28500",
      "name": "Transfers In",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "71000",
      "name": "Collectables (Coins, Stamps, Wine and Other Personal Use Assets)",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "72000",
      "name": "Debt Securities (Bonds, Bills of Exchange, Promissory Notes)",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "72300",
      "name": "Derivatives (Options, Hybrids, Future Contracts)",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "72350",
      "name": "Farming Property",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "72400",
      "name": "Fixed Interest Securities (Australian)",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "72450",
      "name": "Fixed Interest Securities (Australian) - Unitised",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "72500",
      "name": "Fixed Interest Securities (Overseas)",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "72550",
      "name": "Fixed Interest Securities (Overseas) - Unitised",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "72600",
      "name": "Fixtures and Fittings (at written down value)",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "72650",
      "name": "Fixtures and Fittings (at written down value) - Unitised",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "72800",
      "name": "Government Securities (Australian)",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "72900",
      "name": "Government Securities (Overseas)",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "73000",
      "name": "Hybrid Securities with Debt (Swaps, futures contracts, Options.)",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "73200",
      "name": "Interests in Partnerships (Australian)",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "73300",
      "name": "Interests in Partnerships (Overseas)",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "73800",
      "name": "Leased Assets",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "73850",
      "name": "Leased Assets - Unitised",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "73900",
      "name": "Limited Recourse Borrowing Arrangements",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "74000",
      "name": "Insurance Policies",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "74050",
      "name": "Insurance Policies - Unitised",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "74200",
      "name": "Loans to Associated Entities (In house loans)",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "74250",
      "name": "Loans to Associated Entities (In house loans) - Unitised",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "74700",
      "name": "Managed Investments (Australian)",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "74800",
      "name": "Managed Investments (Overseas)",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "75000",
      "name": "Mortgage Loans (Australian)",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "75100",
      "name": "Mortgage Loans (Overseas)",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "75500",
      "name": "Motor Vehicles (at written down value)",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "75550",
      "name": "Motor Vehicles (at written down value) - Unitised",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "76000",
      "name": "Other Assets",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "76100",
      "name": "Other Investments",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "76200",
      "name": "Farming Equipment",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "76500",
      "name": "Plant and Equipment (at written down value)",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "76550",
      "name": "Plant and Equipment (at written down value) - Unitised",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "76800",
      "name": "Pooled Superannuation Trust",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "77200",
      "name": "Real Estate Properties ( Australian - Residential)",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "77250",
      "name": "Real Estate Properties (Australian - Non Residential)",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "77300",
      "name": "Real Estate Properties (Overseas - Residential)",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "77350",
      "name": "Real Estate Properties (Overseas - Non Residential)",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "77600",
      "name": "Shares in Listed Companies (Australian)",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "77700",
      "name": "Shares in Listed Companies (Overseas)",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "77800",
      "name": "Shares in Unlisted Private Companies (Australian)",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "77900",
      "name": "Shares in Unlisted Private Companies (Overseas)",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "78000",
      "name": "Stapled Securities",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "78200",
      "name": "Units in Listed Unit Trusts (Australian)",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "78300",
      "name": "Units in Listed Unit Trusts (Overseas)",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "78400",
      "name": "Units in Unlisted Unit Trusts (Australian)",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "78500",
      "name": "Units in Unlisted Unit Trusts (Overseas)",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "73001",
      "name": "Listed Hybrid & interest rate securities",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "77400",
      "name": "Fixtures & Fittings",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "80500",
      "name": "Amounts owing to other persons",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "81000",
      "name": "Interest Accrued",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "83000",
      "name": "Investment Liabilities",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "85500",
      "name": "Limited Recourse Borrowing Arrangements",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "50010",
      "name": "Opening Balance",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "52420",
      "name": "Contributions",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "52850",
      "name": "Transfers In",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53100",
      "name": "Share of Profit/(Loss)",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53330",
      "name": "Income Tax",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53500",
      "name": "No TFN Excess Contributions Tax",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53800",
      "name": "Contributions Tax",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53900",
      "name": "Insurance Policy Proceeds",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53940",
      "name": "Income Protection Premiums",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53960",
      "name": "Total and Permanent Disability Premiums",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53980",
      "name": "Death Cover Premiums",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "54160",
      "name": "Pensions Paid",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "54500",
      "name": "Benefits Paid/Transfers Out",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "55700",
      "name": "Superannuation Surcharge Tax",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53920",
      "name": "Life Insurance Premiums",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "54000",
      "name": "Management Fees",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "54050",
      "name": "Members Expenses",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "55100",
      "name": "Excess Contributions Tax",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "56100",
      "name": "Internal Transfers In",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "57100",
      "name": "Internal Transfers Out",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "58000",
      "name": "Refund Excess Contributions",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "51900",
      "name": "Division 293 Tax",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "59100",
      "name": "Anti-Detriment Reserve",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "59200",
      "name": "Contribution Reserve",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "59300",
      "name": "Investment Reserve",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "59400",
      "name": "Pension Reserve",
      "accountClass": "Control",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "59500",
      "name": "Self-Insurance Reserve",
      "accountClass": "Control",
      "securityId": null,
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
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Allocation",
        "minCode": 48000,
        "maxCode": 49999,
        "name": "Allocation"
      }
    },
    {
      "code": "48600",
      "name": "Prior Years Under/Over Provision for Income Tax",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Allocation",
        "minCode": 48000,
        "maxCode": 49999,
        "name": "Allocation"
      }
    },
    {
      "code": "48800",
      "name": "Tax Losses Recouped",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Allocation",
        "minCode": 48000,
        "maxCode": 49999,
        "name": "Allocation"
      }
    },
    {
      "code": "48900",
      "name": "Capital Losses Recouped",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Allocation",
        "minCode": 48000,
        "maxCode": 49999,
        "name": "Allocation"
      }
    },
    {
      "code": "49000",
      "name": "Profit/Loss Allocation Account",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Allocation",
        "minCode": 48000,
        "maxCode": 49999,
        "name": "Allocation"
      }
    },
    {
      "code": "49350",
      "name": "Writeback of FITB/PDIT (Unallocated)",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Allocation",
        "minCode": 48000,
        "maxCode": 49999,
        "name": "Allocation"
      }
    },
    {
      "code": "62500",
      "name": "Dividend Reinvestment - Residual Account",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "64000",
      "name": "Formation Expenses",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "65500",
      "name": "Other Assets",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "66000",
      "name": "Prepaid Expenses",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "68000",
      "name": "Sundry Debtors",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "30100",
      "name": "Accountancy Fees",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "30200",
      "name": "Administration Costs",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "30400",
      "name": "ATO Supervisory Levy",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "30500",
      "name": "Advertising",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "30700",
      "name": "Auditor's Remuneration",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "30800",
      "name": "ASIC Fees",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "30900",
      "name": "Advisor Fees",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "31500",
      "name": "Bank Charges",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "32800",
      "name": "Commission",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "35000",
      "name": "General Expenses",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "37700",
      "name": "Interest Paid - ATO General Interest",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "37900",
      "name": "Interest Paid",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "38000",
      "name": "Insurance",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "38200",
      "name": "Fines",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "38700",
      "name": "Legal Fees",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "39700",
      "name": "Light and Power - All Properties",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "41800",
      "name": "Postage, Printing and Stationery",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "41910",
      "name": "Property Expenses - Non Specified",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "43300",
      "name": "Salaries and Wages",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "44700",
      "name": "Telephone",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "47500",
      "name": "Trustee Fees",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "24700",
      "name": "Changes in Market Values of Investments",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "24800",
      "name": "Changes in Market Values of Other Assets",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "25100",
      "name": "Interest Received ATO General Interest Charge",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "84000",
      "name": "GST Payable/Refundable",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "84500",
      "name": "Income in Advance",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "85000",
      "name": "Income Tax Payable/Refundable",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "86000",
      "name": "PAYG Payable",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "88000",
      "name": "Sundry Creditors",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "89000",
      "name": "Deferred Tax Liability/Asset",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "89990",
      "name": "Migration Suspense Account",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "59600",
      "name": "Unallocated Anti-Detriment Reserve",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "59650",
      "name": "Unallocated Contribution Reserve",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "59700",
      "name": "Unallocated Investment Reserve",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "59750",
      "name": "Unallocated Pension Reserve",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "59800",
      "name": "Unallocated Self-Insurance Reserve",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "91000",
      "name": "Bank Data Clearing Account",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Unallocated",
        "minCode": 90000,
        "maxCode": 99999,
        "name": "Unallocated"
      }
    },
    {
      "code": "92000",
      "name": "Investment Income Data Clearing Account",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Unallocated",
        "minCode": 90000,
        "maxCode": 99999,
        "name": "Unallocated"
      }
    },
    {
      "code": "94910",
      "name": "Investment Movement Data Clearing Account",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Unallocated",
        "minCode": 90000,
        "maxCode": 99999,
        "name": "Unallocated"
      }
    },
    {
      "code": "94920",
      "name": "Member Data Clearing Account",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Unallocated",
        "minCode": 90000,
        "maxCode": 99999,
        "name": "Unallocated"
      }
    },
    {
      "code": "94930",
      "name": "Pension Data Clearing Account",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Unallocated",
        "minCode": 90000,
        "maxCode": 99999,
        "name": "Unallocated"
      }
    },
    {
      "code": "99800",
      "name": "Unspecified Data Clearing Account",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Unallocated",
        "minCode": 90000,
        "maxCode": 99999,
        "name": "Unallocated"
      }
    },
    {
      "code": "99900",
      "name": "Manual Suspense Account",
      "accountClass": "Normal",
      "securityId": null,
      "chartAccountType": {
        "label": "Unallocated",
        "minCode": 90000,
        "maxCode": 99999,
        "name": "Unallocated"
      }
    },
    {
      "code": "27500",
      "name": "(Proceeds from Insurance Policies) lAll, eiiigeeif - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "28500",
      "name": "(Transfers In) lAll, eiiigeeif - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39000",
      "name": "(Life Insurance Premiums) lAll, eiiigeeif - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39300",
      "name": "(Life Insurance Premiums (Non Deductible)) lAll, eiiigeeif - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39400",
      "name": "(Income Protection Premiums) lAll, eiiigeeif - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39450",
      "name": "(Income Protection Premiums (Non Deductible)) lAll, eiiigeeif - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39500",
      "name": "(Total and Permanent Disability Premiums) lAll, eiiigeeif - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39550",
      "name": "(Total and Permanent Disability Premiums (Non Deductible)) lAll, eiiigeeif - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39600",
      "name": "(Death Cover Premiums) lAll, eiiigeeif - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39650",
      "name": "(Death Cover Premiums (Non Deductible)) lAll, eiiigeeif - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "40000",
      "name": "(Management Fees) lAll, eiiigeeif - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "40500",
      "name": "(Members Expenses) lAll, eiiigeeif - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "41600",
      "name": "(Pensions Paid) lAll, eiiigeeif - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "44000",
      "name": "(Excess Contributions Tax) lAll, eiiigeeif - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "46000",
      "name": "(Benefits Paid/Transfers Out) lAll, eiiigeeif - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "46600",
      "name": "(Refund Excess Contributions) lAll, eiiigeeif - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "49300",
      "name": "(Writeback of Deferred Tax) lAll, eiiigeeif - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "50010",
      "name": "(Opening Balance) lAll, eiiigeeif - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "52850",
      "name": "(Transfers In) lAll, eiiigeeif - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53100",
      "name": "(Share of Profit/(Loss)) lAll, eiiigeeif - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53330",
      "name": "(Income Tax) lAll, eiiigeeif - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53800",
      "name": "(Contributions Tax) lAll, eiiigeeif - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53900",
      "name": "(Insurance Policy Proceeds) lAll, eiiigeeif - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53920",
      "name": "(Life Insurance Premiums) lAll, eiiigeeif - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53940",
      "name": "(Income Protection Premiums) lAll, eiiigeeif - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53960",
      "name": "(Total and Permanent Disability Premiums) lAll, eiiigeeif - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53980",
      "name": "(Death Cover Premiums) lAll, eiiigeeif - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "54000",
      "name": "(Management Fees) lAll, eiiigeeif - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "54050",
      "name": "(Members Expenses) lAll, eiiigeeif - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "54160",
      "name": "(Pensions Paid) lAll, eiiigeeif - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "54500",
      "name": "(Benefits Paid/Transfers Out) lAll, eiiigeeif - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "55100",
      "name": "(Excess Contributions Tax) lAll, eiiigeeif - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "55700",
      "name": "(Superannuation Surcharge Tax) lAll, eiiigeeif - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "56100",
      "name": "(Internal Transfers In) lAll, eiiigeeif - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "57100",
      "name": "(Internal Transfers Out) lAll, eiiigeeif - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "58000",
      "name": "(Refund Excess Contributions) lAll, eiiigeeif - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "59100",
      "name": "(Anti-Detriment Reserve) lAll, eiiigeeif - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "59300",
      "name": "(Investment Reserve) lAll, eiiigeeif - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "59400",
      "name": "(Pension Reserve) lAll, eiiigeeif - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "59500",
      "name": "(Self-Insurance Reserve) lAll, eiiigeeif - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "27500",
      "name": "(Proceeds from Insurance Policies) llle, yusLyluulSsa - Pension (MARKET LINKED)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "28500",
      "name": "(Transfers In) llle, yusLyluulSsa - Pension (MARKET LINKED)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39000",
      "name": "(Life Insurance Premiums) llle, yusLyluulSsa - Pension (MARKET LINKED)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39300",
      "name": "(Life Insurance Premiums (Non Deductible)) llle, yusLyluulSsa - Pension (MARKET LINKED)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39400",
      "name": "(Income Protection Premiums) llle, yusLyluulSsa - Pension (MARKET LINKED)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39450",
      "name": "(Income Protection Premiums (Non Deductible)) llle, yusLyluulSsa - Pension (MARKET LINKED)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39500",
      "name": "(Total and Permanent Disability Premiums) llle, yusLyluulSsa - Pension (MARKET LINKED)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39550",
      "name": "(Total and Permanent Disability Premiums (Non Deductible)) llle, yusLyluulSsa - Pension (MARKET LINKED)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39600",
      "name": "(Death Cover Premiums) llle, yusLyluulSsa - Pension (MARKET LINKED)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39650",
      "name": "(Death Cover Premiums (Non Deductible)) llle, yusLyluulSsa - Pension (MARKET LINKED)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "40000",
      "name": "(Management Fees) llle, yusLyluulSsa - Pension (MARKET LINKED)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "40500",
      "name": "(Members Expenses) llle, yusLyluulSsa - Pension (MARKET LINKED)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "41600",
      "name": "(Pensions Paid) llle, yusLyluulSsa - Pension (MARKET LINKED)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "44000",
      "name": "(Excess Contributions Tax) llle, yusLyluulSsa - Pension (MARKET LINKED)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "46000",
      "name": "(Benefits Paid/Transfers Out) llle, yusLyluulSsa - Pension (MARKET LINKED)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "46600",
      "name": "(Refund Excess Contributions) llle, yusLyluulSsa - Pension (MARKET LINKED)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "49300",
      "name": "(Writeback of Deferred Tax) llle, yusLyluulSsa - Pension (MARKET LINKED)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "50010",
      "name": "(Opening Balance) llle, yusLyluulSsa - Pension (MARKET LINKED)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "52850",
      "name": "(Transfers In) llle, yusLyluulSsa - Pension (MARKET LINKED)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53100",
      "name": "(Share of Profit/(Loss)) llle, yusLyluulSsa - Pension (MARKET LINKED)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53330",
      "name": "(Income Tax) llle, yusLyluulSsa - Pension (MARKET LINKED)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53800",
      "name": "(Contributions Tax) llle, yusLyluulSsa - Pension (MARKET LINKED)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53900",
      "name": "(Insurance Policy Proceeds) llle, yusLyluulSsa - Pension (MARKET LINKED)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53920",
      "name": "(Life Insurance Premiums) llle, yusLyluulSsa - Pension (MARKET LINKED)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53940",
      "name": "(Income Protection Premiums) llle, yusLyluulSsa - Pension (MARKET LINKED)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53960",
      "name": "(Total and Permanent Disability Premiums) llle, yusLyluulSsa - Pension (MARKET LINKED)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53980",
      "name": "(Death Cover Premiums) llle, yusLyluulSsa - Pension (MARKET LINKED)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "54000",
      "name": "(Management Fees) llle, yusLyluulSsa - Pension (MARKET LINKED)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "54050",
      "name": "(Members Expenses) llle, yusLyluulSsa - Pension (MARKET LINKED)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "54160",
      "name": "(Pensions Paid) llle, yusLyluulSsa - Pension (MARKET LINKED)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "54500",
      "name": "(Benefits Paid/Transfers Out) llle, yusLyluulSsa - Pension (MARKET LINKED)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "55100",
      "name": "(Excess Contributions Tax) llle, yusLyluulSsa - Pension (MARKET LINKED)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "55700",
      "name": "(Superannuation Surcharge Tax) llle, yusLyluulSsa - Pension (MARKET LINKED)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "56100",
      "name": "(Internal Transfers In) llle, yusLyluulSsa - Pension (MARKET LINKED)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "57100",
      "name": "(Internal Transfers Out) llle, yusLyluulSsa - Pension (MARKET LINKED)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "58000",
      "name": "(Refund Excess Contributions) llle, yusLyluulSsa - Pension (MARKET LINKED)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "59100",
      "name": "(Anti-Detriment Reserve) llle, yusLyluulSsa - Pension (MARKET LINKED)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "59300",
      "name": "(Investment Reserve) llle, yusLyluulSsa - Pension (MARKET LINKED)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "59400",
      "name": "(Pension Reserve) llle, yusLyluulSsa - Pension (MARKET LINKED)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "59500",
      "name": "(Self-Insurance Reserve) llle, yusLyluulSsa - Pension (MARKET LINKED)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "27500",
      "name": "(Proceeds from Insurance Policies) llle, yusLyluulSsa - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "28500",
      "name": "(Transfers In) llle, yusLyluulSsa - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39000",
      "name": "(Life Insurance Premiums) llle, yusLyluulSsa - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39300",
      "name": "(Life Insurance Premiums (Non Deductible)) llle, yusLyluulSsa - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39400",
      "name": "(Income Protection Premiums) llle, yusLyluulSsa - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39450",
      "name": "(Income Protection Premiums (Non Deductible)) llle, yusLyluulSsa - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39500",
      "name": "(Total and Permanent Disability Premiums) llle, yusLyluulSsa - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39550",
      "name": "(Total and Permanent Disability Premiums (Non Deductible)) llle, yusLyluulSsa - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39600",
      "name": "(Death Cover Premiums) llle, yusLyluulSsa - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39650",
      "name": "(Death Cover Premiums (Non Deductible)) llle, yusLyluulSsa - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "40000",
      "name": "(Management Fees) llle, yusLyluulSsa - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "40500",
      "name": "(Members Expenses) llle, yusLyluulSsa - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "41600",
      "name": "(Pensions Paid) llle, yusLyluulSsa - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "44000",
      "name": "(Excess Contributions Tax) llle, yusLyluulSsa - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "46000",
      "name": "(Benefits Paid/Transfers Out) llle, yusLyluulSsa - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "46600",
      "name": "(Refund Excess Contributions) llle, yusLyluulSsa - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "49300",
      "name": "(Writeback of Deferred Tax) llle, yusLyluulSsa - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "50010",
      "name": "(Opening Balance) llle, yusLyluulSsa - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "52850",
      "name": "(Transfers In) llle, yusLyluulSsa - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53100",
      "name": "(Share of Profit/(Loss)) llle, yusLyluulSsa - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53330",
      "name": "(Income Tax) llle, yusLyluulSsa - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53800",
      "name": "(Contributions Tax) llle, yusLyluulSsa - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53900",
      "name": "(Insurance Policy Proceeds) llle, yusLyluulSsa - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53920",
      "name": "(Life Insurance Premiums) llle, yusLyluulSsa - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53940",
      "name": "(Income Protection Premiums) llle, yusLyluulSsa - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53960",
      "name": "(Total and Permanent Disability Premiums) llle, yusLyluulSsa - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53980",
      "name": "(Death Cover Premiums) llle, yusLyluulSsa - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "54000",
      "name": "(Management Fees) llle, yusLyluulSsa - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "54050",
      "name": "(Members Expenses) llle, yusLyluulSsa - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "54160",
      "name": "(Pensions Paid) llle, yusLyluulSsa - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "54500",
      "name": "(Benefits Paid/Transfers Out) llle, yusLyluulSsa - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "55100",
      "name": "(Excess Contributions Tax) llle, yusLyluulSsa - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "55700",
      "name": "(Superannuation Surcharge Tax) llle, yusLyluulSsa - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "56100",
      "name": "(Internal Transfers In) llle, yusLyluulSsa - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "57100",
      "name": "(Internal Transfers Out) llle, yusLyluulSsa - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "58000",
      "name": "(Refund Excess Contributions) llle, yusLyluulSsa - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "59100",
      "name": "(Anti-Detriment Reserve) llle, yusLyluulSsa - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "59300",
      "name": "(Investment Reserve) llle, yusLyluulSsa - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "59400",
      "name": "(Pension Reserve) llle, yusLyluulSsa - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "59500",
      "name": "(Self-Insurance Reserve) llle, yusLyluulSsa - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "24200",
      "name": "(Contributions) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "27500",
      "name": "(Proceeds from Insurance Policies) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "28500",
      "name": "(Transfers In) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39000",
      "name": "(Life Insurance Premiums) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39300",
      "name": "(Life Insurance Premiums (Non Deductible)) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39400",
      "name": "(Income Protection Premiums) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39450",
      "name": "(Income Protection Premiums (Non Deductible)) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39500",
      "name": "(Total and Permanent Disability Premiums) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39550",
      "name": "(Total and Permanent Disability Premiums (Non Deductible)) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39600",
      "name": "(Death Cover Premiums) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39650",
      "name": "(Death Cover Premiums (Non Deductible)) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "40000",
      "name": "(Management Fees) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "40500",
      "name": "(Members Expenses) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "44000",
      "name": "(Excess Contributions Tax) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "46000",
      "name": "(Benefits Paid/Transfers Out) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "46600",
      "name": "(Refund Excess Contributions) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "48700",
      "name": "(Contributions Tax (Surcharge)) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "49300",
      "name": "(Writeback of Deferred Tax) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "50010",
      "name": "(Opening Balance) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "52420",
      "name": "(Contributions) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "52850",
      "name": "(Transfers In) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53100",
      "name": "(Share of Profit/(Loss)) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53330",
      "name": "(Income Tax) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53500",
      "name": "(No TFN Excess Contributions Tax) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53800",
      "name": "(Contributions Tax) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53900",
      "name": "(Insurance Policy Proceeds) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53920",
      "name": "(Life Insurance Premiums) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53940",
      "name": "(Income Protection Premiums) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53960",
      "name": "(Total and Permanent Disability Premiums) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53980",
      "name": "(Death Cover Premiums) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "54000",
      "name": "(Management Fees) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "54050",
      "name": "(Members Expenses) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "54500",
      "name": "(Benefits Paid/Transfers Out) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "55100",
      "name": "(Excess Contributions Tax) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "55700",
      "name": "(Superannuation Surcharge Tax) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "56100",
      "name": "(Internal Transfers In) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "57100",
      "name": "(Internal Transfers Out) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "58000",
      "name": "(Refund Excess Contributions) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "59200",
      "name": "(Contribution Reserve) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "59100",
      "name": "(Anti-Detriment Reserve) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "59300",
      "name": "(Investment Reserve) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "59400",
      "name": "(Pension Reserve) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "59500",
      "name": "(Self-Insurance Reserve) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "24200",
      "name": "(Contributions) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "27500",
      "name": "(Proceeds from Insurance Policies) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "28500",
      "name": "(Transfers In) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39000",
      "name": "(Life Insurance Premiums) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39300",
      "name": "(Life Insurance Premiums (Non Deductible)) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39400",
      "name": "(Income Protection Premiums) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39450",
      "name": "(Income Protection Premiums (Non Deductible)) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39500",
      "name": "(Total and Permanent Disability Premiums) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39550",
      "name": "(Total and Permanent Disability Premiums (Non Deductible)) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39600",
      "name": "(Death Cover Premiums) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "39650",
      "name": "(Death Cover Premiums (Non Deductible)) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "40000",
      "name": "(Management Fees) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "40500",
      "name": "(Members Expenses) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "44000",
      "name": "(Excess Contributions Tax) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "46000",
      "name": "(Benefits Paid/Transfers Out) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "46600",
      "name": "(Refund Excess Contributions) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "48700",
      "name": "(Contributions Tax (Surcharge)) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "49300",
      "name": "(Writeback of Deferred Tax) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "50010",
      "name": "(Opening Balance) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "52420",
      "name": "(Contributions) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "52850",
      "name": "(Transfers In) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53100",
      "name": "(Share of Profit/(Loss)) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53330",
      "name": "(Income Tax) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53500",
      "name": "(No TFN Excess Contributions Tax) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53800",
      "name": "(Contributions Tax) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53900",
      "name": "(Insurance Policy Proceeds) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53920",
      "name": "(Life Insurance Premiums) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53940",
      "name": "(Income Protection Premiums) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53960",
      "name": "(Total and Permanent Disability Premiums) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "53980",
      "name": "(Death Cover Premiums) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "54000",
      "name": "(Management Fees) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "54050",
      "name": "(Members Expenses) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "54500",
      "name": "(Benefits Paid/Transfers Out) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "55100",
      "name": "(Excess Contributions Tax) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "55700",
      "name": "(Superannuation Surcharge Tax) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "56100",
      "name": "(Internal Transfers In) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "57100",
      "name": "(Internal Transfers Out) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "58000",
      "name": "(Refund Excess Contributions) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "59200",
      "name": "(Contribution Reserve) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "59100",
      "name": "(Anti-Detriment Reserve) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "59300",
      "name": "(Investment Reserve) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "59400",
      "name": "(Pension Reserve) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "59500",
      "name": "(Self-Insurance Reserve) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "83000",
      "name": "DDH Graham Limited",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "26500",
      "name": "DDH Graham Limited",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "37500",
      "name": "DDH Graham Limited",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "25000",
      "name": "DDH Graham Limited",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "60400",
      "name": "DDH Graham Limited",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset - Bank",
        "minCode": 60400,
        "maxCode": 60800,
        "name": "AssetBank"
      }
    },
    {
      "code": "83000",
      "name": "CommSec CDIA Account (59055)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "26500",
      "name": "CommSec CDIA Account (59055)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "37500",
      "name": "CommSec CDIA Account (59055)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "25000",
      "name": "CommSec CDIA Account (59055)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "60400",
      "name": "CommSec CDIA Account (59055)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset - Bank",
        "minCode": 60400,
        "maxCode": 60800,
        "name": "AssetBank"
      }
    },
    {
      "code": "83000",
      "name": "Commsec Cash Account (37900)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "26500",
      "name": "Commsec Cash Account (37900)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "37500",
      "name": "Commsec Cash Account (37900)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "25000",
      "name": "Commsec Cash Account (37900)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "60400",
      "name": "Commsec Cash Account (37900)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset - Bank",
        "minCode": 60400,
        "maxCode": 60800,
        "name": "AssetBank"
      }
    },
    {
      "code": "65000",
      "name": "ANZ TD (11144) Exp: 18/08/2013",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "25000",
      "name": "ANZ TD (11144) Exp: 18/08/2013",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "81000",
      "name": "ANZ TD (11144) Exp: 18/08/2013",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "83000",
      "name": "ANZ TD (11144) Exp: 18/08/2013",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "37500",
      "name": "ANZ TD (11144) Exp: 18/08/2013",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "72450",
      "name": "ANZ TD (11144) Exp: 18/08/2013",
      "accountClass": "Sub Account",
      "securityId": 68386095,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "65000",
      "name": "DDH Graham TD (79022) Exp: 13/08/2013",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "25000",
      "name": "DDH Graham TD (79022) Exp: 13/08/2013",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "81000",
      "name": "DDH Graham TD (79022) Exp: 13/08/2013",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "83000",
      "name": "DDH Graham TD (79022) Exp: 13/08/2013",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "37500",
      "name": "DDH Graham TD (79022) Exp: 13/08/2013",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "72450",
      "name": "DDH Graham TD (79022) Exp: 13/08/2013",
      "accountClass": "Sub Account",
      "securityId": 68386096,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "65000",
      "name": "DDH Graham TD (24050) Exp: 11/11/2013",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "25000",
      "name": "DDH Graham TD (24050) Exp: 11/11/2013",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "81000",
      "name": "DDH Graham TD (24050) Exp: 11/11/2013",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "83000",
      "name": "DDH Graham TD (24050) Exp: 11/11/2013",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "37500",
      "name": "DDH Graham TD (24050) Exp: 11/11/2013",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "72450",
      "name": "DDH Graham TD (24050) Exp: 11/11/2013",
      "accountClass": "Sub Account",
      "securityId": 68386097,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "83000",
      "name": "DDH Graham TD (82794)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "25000",
      "name": "DDH Graham TD (82794)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "37500",
      "name": "DDH Graham TD (82794)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "81000",
      "name": "DDH Graham TD (82794)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "65000",
      "name": "DDH Graham TD (82794)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "72400",
      "name": "DDH Graham TD (82794)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "83000",
      "name": "DDH Graham TD (82797)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "25000",
      "name": "DDH Graham TD (82797)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "37500",
      "name": "DDH Graham TD (82797)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "81000",
      "name": "DDH Graham TD (82797)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "65000",
      "name": "DDH Graham TD (82797)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "72400",
      "name": "DDH Graham TD (82797)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "83000",
      "name": "ANZ TD (11144)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "25000",
      "name": "ANZ TD (11144)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "37500",
      "name": "ANZ TD (11144)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "81000",
      "name": "ANZ TD (11144)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "65000",
      "name": "ANZ TD (11144)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "72400",
      "name": "ANZ TD (11144)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "83000",
      "name": "DDH Graham TD (33585)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "25000",
      "name": "DDH Graham TD (33585)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "37500",
      "name": "DDH Graham TD (33585)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "81000",
      "name": "DDH Graham TD (33585)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "65000",
      "name": "DDH Graham TD (33585)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "72400",
      "name": "DDH Graham TD (33585)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "65000",
      "name": "DDH Graham TD (71261) Exp:10/02/14",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "25000",
      "name": "DDH Graham TD (71261) Exp:10/02/14",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "81000",
      "name": "DDH Graham TD (71261) Exp:10/02/14",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "83000",
      "name": "DDH Graham TD (71261) Exp:10/02/14",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "37500",
      "name": "DDH Graham TD (71261) Exp:10/02/14",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "72450",
      "name": "DDH Graham TD (71261) Exp:10/02/14",
      "accountClass": "Sub Account",
      "securityId": 68386098,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "65000",
      "name": "DDH Graham (15831) Exp:11/02/14",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "25000",
      "name": "DDH Graham (15831) Exp:11/02/14",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "81000",
      "name": "DDH Graham (15831) Exp:11/02/14",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "83000",
      "name": "DDH Graham (15831) Exp:11/02/14",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "37500",
      "name": "DDH Graham (15831) Exp:11/02/14",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "72450",
      "name": "DDH Graham (15831) Exp:11/02/14",
      "accountClass": "Sub Account",
      "securityId": 68386099,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "41950",
      "name": "Suite 2, Summit Ridge Falls Creek VIC",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "41990",
      "name": "Suite 2, Summit Ridge Falls Creek VIC",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42120",
      "name": "Suite 2, Summit Ridge Falls Creek VIC",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "41960",
      "name": "Suite 2, Summit Ridge Falls Creek VIC",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42150",
      "name": "Suite 2, Summit Ridge Falls Creek VIC",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42030",
      "name": "Suite 2, Summit Ridge Falls Creek VIC",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42000",
      "name": "Suite 2, Summit Ridge Falls Creek VIC",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42140",
      "name": "Suite 2, Summit Ridge Falls Creek VIC",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "41970",
      "name": "Suite 2, Summit Ridge Falls Creek VIC",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "37500",
      "name": "Suite 2, Summit Ridge Falls Creek VIC",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42080",
      "name": "Suite 2, Summit Ridge Falls Creek VIC",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42060",
      "name": "Suite 2, Summit Ridge Falls Creek VIC",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "41980",
      "name": "Suite 2, Summit Ridge Falls Creek VIC",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42050",
      "name": "Suite 2, Summit Ridge Falls Creek VIC",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "28000",
      "name": "Suite 2, Summit Ridge Falls Creek VIC",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "42070",
      "name": "Suite 2, Summit Ridge Falls Creek VIC",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "41940",
      "name": "Suite 2, Summit Ridge Falls Creek VIC",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "41930",
      "name": "Suite 2, Summit Ridge Falls Creek VIC",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "33400",
      "name": "Suite 2, Summit Ridge Falls Creek VIC",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42130",
      "name": "Suite 2, Summit Ridge Falls Creek VIC",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "83000",
      "name": "Suite 2, Summit Ridge Falls Creek VIC",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "42110",
      "name": "Suite 2, Summit Ridge Falls Creek VIC",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42100",
      "name": "Suite 2, Summit Ridge Falls Creek VIC",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42090",
      "name": "Suite 2, Summit Ridge Falls Creek VIC",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42020",
      "name": "Suite 2, Summit Ridge Falls Creek VIC",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "41920",
      "name": "Suite 2, Summit Ridge Falls Creek VIC",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42040",
      "name": "Suite 2, Summit Ridge Falls Creek VIC",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42010",
      "name": "Suite 2, Summit Ridge Falls Creek VIC",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "77200",
      "name": "Suite 2, Summit Ridge Falls Creek VIC",
      "accountClass": "Sub Account",
      "securityId": 68386100,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "41950",
      "name": "Bottle Tree Gardens Motel, Cnr Charles/Bowen Streets Roma",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "41990",
      "name": "Bottle Tree Gardens Motel, Cnr Charles/Bowen Streets Roma",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42120",
      "name": "Bottle Tree Gardens Motel, Cnr Charles/Bowen Streets Roma",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "41960",
      "name": "Bottle Tree Gardens Motel, Cnr Charles/Bowen Streets Roma",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42150",
      "name": "Bottle Tree Gardens Motel, Cnr Charles/Bowen Streets Roma",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42030",
      "name": "Bottle Tree Gardens Motel, Cnr Charles/Bowen Streets Roma",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42000",
      "name": "Bottle Tree Gardens Motel, Cnr Charles/Bowen Streets Roma",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42140",
      "name": "Bottle Tree Gardens Motel, Cnr Charles/Bowen Streets Roma",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "41970",
      "name": "Bottle Tree Gardens Motel, Cnr Charles/Bowen Streets Roma",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "37500",
      "name": "Bottle Tree Gardens Motel, Cnr Charles/Bowen Streets Roma",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42080",
      "name": "Bottle Tree Gardens Motel, Cnr Charles/Bowen Streets Roma",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42060",
      "name": "Bottle Tree Gardens Motel, Cnr Charles/Bowen Streets Roma",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "41980",
      "name": "Bottle Tree Gardens Motel, Cnr Charles/Bowen Streets Roma",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42050",
      "name": "Bottle Tree Gardens Motel, Cnr Charles/Bowen Streets Roma",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "28000",
      "name": "Bottle Tree Gardens Motel, Cnr Charles/Bowen Streets Roma",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "42070",
      "name": "Bottle Tree Gardens Motel, Cnr Charles/Bowen Streets Roma",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "41940",
      "name": "Bottle Tree Gardens Motel, Cnr Charles/Bowen Streets Roma",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "41930",
      "name": "Bottle Tree Gardens Motel, Cnr Charles/Bowen Streets Roma",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "33400",
      "name": "Bottle Tree Gardens Motel, Cnr Charles/Bowen Streets Roma",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42130",
      "name": "Bottle Tree Gardens Motel, Cnr Charles/Bowen Streets Roma",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "83000",
      "name": "Bottle Tree Gardens Motel, Cnr Charles/Bowen Streets Roma",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "42110",
      "name": "Bottle Tree Gardens Motel, Cnr Charles/Bowen Streets Roma",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42100",
      "name": "Bottle Tree Gardens Motel, Cnr Charles/Bowen Streets Roma",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42090",
      "name": "Bottle Tree Gardens Motel, Cnr Charles/Bowen Streets Roma",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42020",
      "name": "Bottle Tree Gardens Motel, Cnr Charles/Bowen Streets Roma",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "41920",
      "name": "Bottle Tree Gardens Motel, Cnr Charles/Bowen Streets Roma",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42040",
      "name": "Bottle Tree Gardens Motel, Cnr Charles/Bowen Streets Roma",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "42010",
      "name": "Bottle Tree Gardens Motel, Cnr Charles/Bowen Streets Roma",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "77200",
      "name": "Bottle Tree Gardens Motel, Cnr Charles/Bowen Streets Roma",
      "accountClass": "Sub Account",
      "securityId": 68386101,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "77600",
      "name": "Australia and NZ Banking Group",
      "accountClass": "Sub Account",
      "securityId": 728641,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "83000",
      "name": "Australia and NZ Banking Group",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "37500",
      "name": "Australia and NZ Banking Group",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "62000",
      "name": "Australia and NZ Banking Group",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "23900",
      "name": "Australia and NZ Banking Group",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "77600",
      "name": "Commonwealth Bank of Australia",
      "accountClass": "Sub Account",
      "securityId": 717279,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "37500",
      "name": "Commonwealth Bank of Australia",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "83000",
      "name": "Commonwealth Bank of Australia",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "23900",
      "name": "Commonwealth Bank of Australia",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "62000",
      "name": "Commonwealth Bank of Australia",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "77600",
      "name": "Csr Limited",
      "accountClass": "Sub Account",
      "securityId": 723139,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "62000",
      "name": "Csr Limited",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "23900",
      "name": "Csr Limited",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "37500",
      "name": "Csr Limited",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "83000",
      "name": "Csr Limited",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "77600",
      "name": "Envestra Limited",
      "accountClass": "Sub Account",
      "securityId": 734260,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "23900",
      "name": "Envestra Limited",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "62000",
      "name": "Envestra Limited",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "37500",
      "name": "Envestra Limited",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "83000",
      "name": "Envestra Limited",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "77600",
      "name": "Goodman Fielder Limited.",
      "accountClass": "Sub Account",
      "securityId": 701767,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "37500",
      "name": "Goodman Fielder Limited.",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "62000",
      "name": "Goodman Fielder Limited.",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "83000",
      "name": "Goodman Fielder Limited.",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "23900",
      "name": "Goodman Fielder Limited.",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "77600",
      "name": "National Aust. Bank",
      "accountClass": "Sub Account",
      "securityId": 731230,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "83000",
      "name": "National Aust. Bank",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "23900",
      "name": "National Aust. Bank",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "37500",
      "name": "National Aust. Bank",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "62000",
      "name": "National Aust. Bank",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "77600",
      "name": "Schaffer Corporation Limited",
      "accountClass": "Sub Account",
      "securityId": 700188,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "37500",
      "name": "Schaffer Corporation Limited",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "62000",
      "name": "Schaffer Corporation Limited",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "83000",
      "name": "Schaffer Corporation Limited",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "23900",
      "name": "Schaffer Corporation Limited",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "77600",
      "name": "Tabcorp Holdings Limited",
      "accountClass": "Sub Account",
      "securityId": 709174,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "37500",
      "name": "Tabcorp Holdings Limited",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "83000",
      "name": "Tabcorp Holdings Limited",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "23900",
      "name": "Tabcorp Holdings Limited",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "62000",
      "name": "Tabcorp Holdings Limited",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "77600",
      "name": "Tatts Group Limited",
      "accountClass": "Sub Account",
      "securityId": 709245,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "62000",
      "name": "Tatts Group Limited",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "37500",
      "name": "Tatts Group Limited",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "83000",
      "name": "Tatts Group Limited",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "23900",
      "name": "Tatts Group Limited",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "77600",
      "name": "Telstra Corporation Ltd",
      "accountClass": "Sub Account",
      "securityId": 687013,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "23900",
      "name": "Telstra Corporation Ltd",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "83000",
      "name": "Telstra Corporation Ltd",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "62000",
      "name": "Telstra Corporation Ltd",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "37500",
      "name": "Telstra Corporation Ltd",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "77600",
      "name": "Wesfarmers Limited",
      "accountClass": "Sub Account",
      "securityId": 711425,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "23900",
      "name": "Wesfarmers Limited",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "37500",
      "name": "Wesfarmers Limited",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "62000",
      "name": "Wesfarmers Limited",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "83000",
      "name": "Wesfarmers Limited",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "77600",
      "name": "Westpac Banking Corp",
      "accountClass": "Sub Account",
      "securityId": 701417,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "23900",
      "name": "Westpac Banking Corp",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "83000",
      "name": "Westpac Banking Corp",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "62000",
      "name": "Westpac Banking Corp",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "37500",
      "name": "Westpac Banking Corp",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "62000",
      "name": "Australia and New Zealand Banking Group Limited - CPS",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "37500",
      "name": "Australia and New Zealand Banking Group Limited - CPS",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "23900",
      "name": "Australia and New Zealand Banking Group Limited - CPS",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "83000",
      "name": "Australia and New Zealand Banking Group Limited - CPS",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "77600",
      "name": "Australia and New Zealand Banking Group Limited - CPS",
      "accountClass": "Sub Account",
      "securityId": 732607,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "77600",
      "name": "Commonwealth Bank of Aust (CBAPA)",
      "accountClass": "Sub Account",
      "securityId": 688822,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "62000",
      "name": "Commonwealth Bank of Aust (CBAPA)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "37500",
      "name": "Commonwealth Bank of Aust (CBAPA)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "23900",
      "name": "Commonwealth Bank of Aust (CBAPA)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "83000",
      "name": "Commonwealth Bank of Aust (CBAPA)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "62000",
      "name": "GWA Group Limited. - Ordinary Fully Paid",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "37500",
      "name": "GWA Group Limited. - Ordinary Fully Paid",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "23900",
      "name": "GWA Group Limited. - Ordinary Fully Paid",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "83000",
      "name": "GWA Group Limited. - Ordinary Fully Paid",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "77600",
      "name": "GWA Group Limited. - Ordinary Fully Paid",
      "accountClass": "Sub Account",
      "securityId": 702837,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "77600",
      "name": "Echo Entertainment Group Limited",
      "accountClass": "Sub Account",
      "securityId": 713076,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "37500",
      "name": "Echo Entertainment Group Limited",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "83000",
      "name": "Echo Entertainment Group Limited",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "62000",
      "name": "Echo Entertainment Group Limited",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "23900",
      "name": "Echo Entertainment Group Limited",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "62000",
      "name": "Brookfield Infrastructure Partners",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "37500",
      "name": "Brookfield Infrastructure Partners",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "83000",
      "name": "Brookfield Infrastructure Partners",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "23900",
      "name": "Brookfield Infrastructure Partners",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "77700",
      "name": "Brookfield Infrastructure Partners",
      "accountClass": "Sub Account",
      "securityId": 68386102,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "24000",
      "name": "AET&D Holdings No 1 Limited",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "37500",
      "name": "AET&D Holdings No 1 Limited",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "62000",
      "name": "AET&D Holdings No 1 Limited",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "83000",
      "name": "AET&D Holdings No 1 Limited",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "77800",
      "name": "AET&D Holdings No 1 Limited",
      "accountClass": "Sub Account",
      "securityId": 68386103,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "23900",
      "name": "AET&D Holdings No 1 Limited",
      "accountClass": "Sub Account",
      "securityId": 68386103,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "61800",
      "name": "Rubicon America Trust",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "37500",
      "name": "Rubicon America Trust",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "83000",
      "name": "Rubicon America Trust",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "23800",
      "name": "Rubicon America Trust",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "78200",
      "name": "Rubicon America Trust",
      "accountClass": "Sub Account",
      "securityId": 68386104,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "25000",
      "name": "ATO",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "42500",
      "name": "Land Tax",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "62000",
      "name": "MAMBA MINERALS LIMITED",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Asset",
        "minCode": 60000,
        "maxCode": 69999,
        "name": "Asset"
      }
    },
    {
      "code": "37500",
      "name": "MAMBA MINERALS LIMITED",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Expense",
        "minCode": 30000,
        "maxCode": 47999,
        "name": "Expense"
      }
    },
    {
      "code": "23900",
      "name": "MAMBA MINERALS LIMITED",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income",
        "minCode": 20000,
        "maxCode": 29999,
        "name": "Income"
      }
    },
    {
      "code": "83000",
      "name": "MAMBA MINERALS LIMITED",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Liability",
        "minCode": 80000,
        "maxCode": 89999,
        "name": "Liability"
      }
    },
    {
      "code": "77600",
      "name": "MAMBA MINERALS LIMITED",
      "accountClass": "Sub Account",
      "securityId": 689298,
      "chartAccountType": {
        "label": "Investment",
        "minCode": 70000,
        "maxCode": 79999,
        "name": "Investment"
      }
    },
    {
      "code": "48100",
      "name": "(Division 293 Tax) lAll, eiiigeeif - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "51900",
      "name": "(Division 293 Tax) lAll, eiiigeeif - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "48100",
      "name": "(Division 293 Tax) llle, yusLyluulSsa - Pension (MARKET LINKED)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "51900",
      "name": "(Division 293 Tax) llle, yusLyluulSsa - Pension (MARKET LINKED)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "48100",
      "name": "(Division 293 Tax) llle, yusLyluulSsa - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "51900",
      "name": "(Division 293 Tax) llle, yusLyluulSsa - Pension (ABP1)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "48100",
      "name": "(Division 293 Tax) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "51900",
      "name": "(Division 293 Tax) llle, yusLyluulSsa - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    },
    {
      "code": "48100",
      "name": "(Division 293 Tax) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Income - Member",
        "minCode": 0,
        "maxCode": 0,
        "name": "IncomeMember"
      }
    },
    {
      "code": "51900",
      "name": "(Division 293 Tax) lAll, eiiigeeif - Accumulation (Accumulation)",
      "accountClass": "Sub Account",
      "securityId": null,
      "chartAccountType": {
        "label": "Member",
        "minCode": 50000,
        "maxCode": 59999,
        "name": "Member"
      }
    }
  ]
}

```
