# Chart of Accounts - XML

#### cURL Request :

```javascript

curl -X POST https://api-staging.bgl360.com.au/fund/chartAccounts.xml?fundId=0000000048f240bd0148f28816c80017 --header "Authorization:bearer df2f0e40-606f-4311-8066-590732fd126b"

```

#### Response :


```xml

<root xmlns='http://www.bglcorp.com.au'>
	< code='48700' name='Contributions Tax (Surcharge)' accountClass='Control' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='49300' name='Writeback of Deferred Tax' accountClass='Control' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='60100' name='Amounts owing by Other Persons' accountClass='Control' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='61600' name='Contributions Receivable' accountClass='Control' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='61800' name='Distributions Receivable' accountClass='Control' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='62000' name='Dividends Receivable' accountClass='Control' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='65000' name='Interest Receivable' accountClass='Control' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='60200' name='Dividend Reinvestment Plan Balance' accountClass='Control' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='62501' name='DRP Residual Value - Westfarmer Ltd' accountClass='Control' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='65200' name='Interest Receivable' accountClass='Control' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='68101' name='re 11/42 Stud Road Bayswater' accountClass='Control' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='62502' name='DRP Residual Value - Westfarmer Ltd' accountClass='Control' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='68001' name='Other Debtors' accountClass='Control' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='60400' name='Bank Accounts' accountClass='Control' securityId='' chartAccountType='{label=Asset - Bank, minCode=60400, maxCode=60800}' />
	< code='60800' name='Term Deposits' accountClass='Control' securityId='' chartAccountType='{label=Asset - Bank, minCode=60400, maxCode=60800}' />
	< code='33400' name='Depreciation' accountClass='Control' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='37500' name='Investment Expenses' accountClass='Control' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='41920' name='Property Expenses - Advertising' accountClass='Control' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='41930' name='Property Expenses - Agents Management Fees' accountClass='Control' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='41940' name='Property Expenses - Agents Commissions' accountClass='Control' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='41950' name='Property Expenses - Cleaning' accountClass='Control' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='41960' name='Property Expenses - Council Rates' accountClass='Control' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='41970' name='Property Expenses - Garden and Lawn' accountClass='Control' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='41980' name='Property Expenses - Insurance Premium' accountClass='Control' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='41990' name='Property Expenses - Interest on Deposit Paid' accountClass='Control' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42000' name='Property Expenses - Interest on Late Settlement Paid' accountClass='Control' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42010' name='Property Expenses - Interest on Loans' accountClass='Control' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42020' name='Property Expenses - Land Tax' accountClass='Control' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42030' name='Property Expenses - Legal Fees' accountClass='Control' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42040' name='Property Expenses - Pest Control' accountClass='Control' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42050' name='Property Expenses - Property Capital Improvement' accountClass='Control' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42060' name='Property Expenses - Repairs Maintenance' accountClass='Control' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42070' name='Property Expenses - Settlement Agent Fees' accountClass='Control' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42080' name='Property Expenses - Stamp Duty' accountClass='Control' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42090' name='Property Expenses - Stationery, Phone and Postage' accountClass='Control' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42100' name='Property Expenses - Strata Levy Fees' accountClass='Control' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42110' name='Property Expenses - Sundry Expenses' accountClass='Control' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42120' name='Property Expenses - Title Fees' accountClass='Control' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42130' name='Property Expenses - Travel' accountClass='Control' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42140' name='Property Expenses - Vendor Solicitor&apos;s Fees' accountClass='Control' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42150' name='Property Expenses - Water Rates' accountClass='Control' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='33500' name='Capital Allowance' accountClass='Control' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42500' name='Rental Property Expenses' accountClass='Control' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42501' name='Viridian - ACT' accountClass='Control' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42502' name='Rental Property Expenses' accountClass='Control' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='39000' name='Life Insurance Premiums' accountClass='Control' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39300' name='Life Insurance Premiums (Non Deductible)' accountClass='Control' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39400' name='Income Protection Premiums' accountClass='Control' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39450' name='Income Protection Premiums (Non Deductible)' accountClass='Control' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39500' name='Total and Permanent Disability Premiums' accountClass='Control' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39550' name='Total and Permanent Disability Premiums (Non Deductible)' accountClass='Control' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39600' name='Death Cover Premiums' accountClass='Control' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39650' name='Death Cover Premiums (Non Deductible)' accountClass='Control' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='40000' name='Management Fees' accountClass='Control' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='40500' name='Members Expenses' accountClass='Control' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='41600' name='Pensions Paid' accountClass='Control' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='44000' name='Excess Contributions Tax' accountClass='Control' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='46000' name='Benefits Paid/Transfers Out' accountClass='Control' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='46600' name='Refund Excess Contributions' accountClass='Control' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='48100' name='Division 293 Tax' accountClass='Control' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='23800' name='Distributions Received' accountClass='Control' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='23900' name='Dividends Received' accountClass='Control' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='24000' name='Private dividends and other excessive non-arms length income' accountClass='Control' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='25000' name='Interest Received' accountClass='Control' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='25200' name='Income in Advance' accountClass='Control' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='25500' name='Lease and Hire Income' accountClass='Control' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='26500' name='Other Investment Income' accountClass='Control' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='27000' name='Partnership Distributions Received' accountClass='Control' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='27800' name='Profit/(Loss) on disposal of depreciable assets' accountClass='Control' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='27850' name='Profit/(Loss) on disposal of leased depreciable assets' accountClass='Control' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='28000' name='Property Income' accountClass='Control' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='25600' name='Lease and Hire Income (Non Taxable)' accountClass='Control' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='26600' name='Other Income - Non assessable' accountClass='Control' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='28100' name='Outgoings received' accountClass='Control' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='25601' name='Lease and Hire Income (Non Taxable)' accountClass='Control' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='26602' name='Other Income - Non assessable' accountClass='Control' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='24200' name='Contributions' accountClass='Control' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='27500' name='Proceeds from Insurance Policies' accountClass='Control' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='28500' name='Transfers In' accountClass='Control' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='71000' name='Collectables (Coins, Stamps, Wine and Other Personal Use Assets)' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='72000' name='Debt Securities (Bonds, Bills of Exchange, Promissory Notes)' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='72300' name='Derivatives (Options, Hybrids, Future Contracts)' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='72350' name='Farming Property' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='72400' name='Fixed Interest Securities (Australian)' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='72450' name='Fixed Interest Securities (Australian) - Unitised' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='72500' name='Fixed Interest Securities (Overseas)' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='72550' name='Fixed Interest Securities (Overseas) - Unitised' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='72600' name='Fixtures and Fittings (at written down value)' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='72650' name='Fixtures and Fittings (at written down value) - Unitised' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='72800' name='Government Securities (Australian)' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='72900' name='Government Securities (Overseas)' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='73000' name='Hybrid Securities with Debt (Swaps, futures contracts, Options.)' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='73200' name='Interests in Partnerships (Australian)' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='73300' name='Interests in Partnerships (Overseas)' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='73800' name='Leased Assets' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='73850' name='Leased Assets - Unitised' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='73900' name='Limited Recourse Borrowing Arrangements' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='74000' name='Insurance Policies' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='74050' name='Insurance Policies - Unitised' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='74200' name='Loans to Associated Entities (In house loans)' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='74250' name='Loans to Associated Entities (In house loans) - Unitised' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='74700' name='Managed Investments (Australian)' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='74800' name='Managed Investments (Overseas)' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='75000' name='Mortgage Loans (Australian)' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='75100' name='Mortgage Loans (Overseas)' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='75500' name='Motor Vehicles (at written down value)' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='75550' name='Motor Vehicles (at written down value) - Unitised' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='76000' name='Other Assets' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='76100' name='Other Investments' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='76200' name='Farming Equipment' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='76500' name='Plant and Equipment (at written down value)' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='76550' name='Plant and Equipment (at written down value) - Unitised' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='76800' name='Pooled Superannuation Trust' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='77200' name='Real Estate Properties ( Australian - Residential)' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='77250' name='Real Estate Properties (Australian - Non Residential)' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='77300' name='Real Estate Properties (Overseas - Residential)' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='77350' name='Real Estate Properties (Overseas - Non Residential)' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='77600' name='Shares in Listed Companies (Australian)' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='77700' name='Shares in Listed Companies (Overseas)' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='77800' name='Shares in Unlisted Private Companies (Australian)' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='77900' name='Shares in Unlisted Private Companies (Overseas)' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='78000' name='Stapled Securities' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='78200' name='Units in Listed Unit Trusts (Australian)' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='78300' name='Units in Listed Unit Trusts (Overseas)' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='78400' name='Units in Unlisted Unit Trusts (Australian)' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='78500' name='Units in Unlisted Unit Trusts (Overseas)' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='73001' name='Listed Hybrid &amp; interest rate securities' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='77400' name='Fixtures &amp; Fittings' accountClass='Control' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='80500' name='Amounts owing to other persons' accountClass='Control' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='81000' name='Interest Accrued' accountClass='Control' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='83000' name='Investment Liabilities' accountClass='Control' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='85500' name='Limited Recourse Borrowing Arrangements' accountClass='Control' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='50010' name='Opening Balance' accountClass='Control' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='52420' name='Contributions' accountClass='Control' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='52850' name='Transfers In' accountClass='Control' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53100' name='Share of Profit/(Loss)' accountClass='Control' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53330' name='Income Tax' accountClass='Control' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53500' name='No TFN Excess Contributions Tax' accountClass='Control' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53800' name='Contributions Tax' accountClass='Control' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53900' name='Insurance Policy Proceeds' accountClass='Control' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53940' name='Income Protection Premiums' accountClass='Control' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53960' name='Total and Permanent Disability Premiums' accountClass='Control' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53980' name='Death Cover Premiums' accountClass='Control' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54160' name='Pensions Paid' accountClass='Control' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54500' name='Benefits Paid/Transfers Out' accountClass='Control' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='55700' name='Superannuation Surcharge Tax' accountClass='Control' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53920' name='Life Insurance Premiums' accountClass='Control' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54000' name='Management Fees' accountClass='Control' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54050' name='Members Expenses' accountClass='Control' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='55100' name='Excess Contributions Tax' accountClass='Control' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='56100' name='Internal Transfers In' accountClass='Control' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='57100' name='Internal Transfers Out' accountClass='Control' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='58000' name='Refund Excess Contributions' accountClass='Control' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='51900' name='Division 293 Tax' accountClass='Control' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='59100' name='Anti-Detriment Reserve' accountClass='Control' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59200' name='Contribution Reserve' accountClass='Control' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59300' name='Investment Reserve' accountClass='Control' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59400' name='Pension Reserve' accountClass='Control' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59500' name='Self-Insurance Reserve' accountClass='Control' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='48500' name='Income Tax Expense' accountClass='Normal' securityId='' chartAccountType='{label=Allocation, minCode=48000, maxCode=49999}' />
	< code='48600' name='Prior Years Under/Over Provision for Income Tax' accountClass='Normal' securityId='' chartAccountType='{label=Allocation, minCode=48000, maxCode=49999}' />
	< code='48800' name='Tax Losses Recouped' accountClass='Normal' securityId='' chartAccountType='{label=Allocation, minCode=48000, maxCode=49999}' />
	< code='48900' name='Capital Losses Recouped' accountClass='Normal' securityId='' chartAccountType='{label=Allocation, minCode=48000, maxCode=49999}' />
	< code='49000' name='Profit/Loss Allocation Account' accountClass='Normal' securityId='' chartAccountType='{label=Allocation, minCode=48000, maxCode=49999}' />
	< code='49350' name='Writeback of FITB/PDIT (Unallocated)' accountClass='Normal' securityId='' chartAccountType='{label=Allocation, minCode=48000, maxCode=49999}' />
	< code='62500' name='Dividend Reinvestment - Residual Account' accountClass='Normal' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='64000' name='Formation Expenses' accountClass='Normal' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='65500' name='Other Assets' accountClass='Normal' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='66000' name='Prepaid Expenses' accountClass='Normal' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='68000' name='Sundry Debtors' accountClass='Normal' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='30100' name='Accountancy Fees' accountClass='Normal' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='30200' name='Administration Costs' accountClass='Normal' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='30400' name='ATO Supervisory Levy' accountClass='Normal' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='30500' name='Advertising' accountClass='Normal' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='30700' name='Auditor&apos;s Remuneration' accountClass='Normal' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='30800' name='ASIC Fees' accountClass='Normal' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='30900' name='Advisor Fees' accountClass='Normal' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='31500' name='Bank Charges' accountClass='Normal' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='32800' name='Commission' accountClass='Normal' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='35000' name='General Expenses' accountClass='Normal' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='37700' name='Interest Paid - ATO General Interest' accountClass='Normal' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='37900' name='Interest Paid' accountClass='Normal' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='38000' name='Insurance' accountClass='Normal' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='38200' name='Fines' accountClass='Normal' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='38700' name='Legal Fees' accountClass='Normal' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='39700' name='Light and Power - All Properties' accountClass='Normal' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='41800' name='Postage, Printing and Stationery' accountClass='Normal' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='41910' name='Property Expenses - Non Specified' accountClass='Normal' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='43300' name='Salaries and Wages' accountClass='Normal' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='44700' name='Telephone' accountClass='Normal' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='47500' name='Trustee Fees' accountClass='Normal' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='24700' name='Changes in Market Values of Investments' accountClass='Normal' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='24800' name='Changes in Market Values of Other Assets' accountClass='Normal' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='25100' name='Interest Received ATO General Interest Charge' accountClass='Normal' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='84000' name='GST Payable/Refundable' accountClass='Normal' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='84500' name='Income in Advance' accountClass='Normal' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='85000' name='Income Tax Payable/Refundable' accountClass='Normal' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='86000' name='PAYG Payable' accountClass='Normal' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='88000' name='Sundry Creditors' accountClass='Normal' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='89000' name='Deferred Tax Liability/Asset' accountClass='Normal' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='89990' name='Migration Suspense Account' accountClass='Normal' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='59600' name='Unallocated Anti-Detriment Reserve' accountClass='Normal' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59650' name='Unallocated Contribution Reserve' accountClass='Normal' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59700' name='Unallocated Investment Reserve' accountClass='Normal' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59750' name='Unallocated Pension Reserve' accountClass='Normal' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59800' name='Unallocated Self-Insurance Reserve' accountClass='Normal' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='91000' name='Bank Data Clearing Account' accountClass='Normal' securityId='' chartAccountType='{label=Unallocated, minCode=90000, maxCode=99999}' />
	< code='92000' name='Investment Income Data Clearing Account' accountClass='Normal' securityId='' chartAccountType='{label=Unallocated, minCode=90000, maxCode=99999}' />
	< code='94910' name='Investment Movement Data Clearing Account' accountClass='Normal' securityId='' chartAccountType='{label=Unallocated, minCode=90000, maxCode=99999}' />
	< code='94920' name='Member Data Clearing Account' accountClass='Normal' securityId='' chartAccountType='{label=Unallocated, minCode=90000, maxCode=99999}' />
	< code='94930' name='Pension Data Clearing Account' accountClass='Normal' securityId='' chartAccountType='{label=Unallocated, minCode=90000, maxCode=99999}' />
	< code='99800' name='Unspecified Data Clearing Account' accountClass='Normal' securityId='' chartAccountType='{label=Unallocated, minCode=90000, maxCode=99999}' />
	< code='99900' name='Manual Suspense Account' accountClass='Normal' securityId='' chartAccountType='{label=Unallocated, minCode=90000, maxCode=99999}' />
	< code='27500' name='(Proceeds from Insurance Policies) drnwArn,  h  JhB rJ - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='28500' name='(Transfers In) drnwArn,  h  JhB rJ - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39000' name='(Life Insurance Premiums) drnwArn,  h  JhB rJ - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39300' name='(Life Insurance Premiums (Non Deductible)) drnwArn,  h  JhB rJ - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39400' name='(Income Protection Premiums) drnwArn,  h  JhB rJ - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39450' name='(Income Protection Premiums (Non Deductible)) drnwArn,  h  JhB rJ - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39500' name='(Total and Permanent Disability Premiums) drnwArn,  h  JhB rJ - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39550' name='(Total and Permanent Disability Premiums (Non Deductible)) drnwArn,  h  JhB rJ - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39600' name='(Death Cover Premiums) drnwArn,  h  JhB rJ - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39650' name='(Death Cover Premiums (Non Deductible)) drnwArn,  h  JhB rJ - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='40000' name='(Management Fees) drnwArn,  h  JhB rJ - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='40500' name='(Members Expenses) drnwArn,  h  JhB rJ - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='41600' name='(Pensions Paid) drnwArn,  h  JhB rJ - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='44000' name='(Excess Contributions Tax) drnwArn,  h  JhB rJ - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='46000' name='(Benefits Paid/Transfers Out) drnwArn,  h  JhB rJ - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='46600' name='(Refund Excess Contributions) drnwArn,  h  JhB rJ - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='49300' name='(Writeback of Deferred Tax) drnwArn,  h  JhB rJ - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='50010' name='(Opening Balance) drnwArn,  h  JhB rJ - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='52850' name='(Transfers In) drnwArn,  h  JhB rJ - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53100' name='(Share of Profit/(Loss)) drnwArn,  h  JhB rJ - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53330' name='(Income Tax) drnwArn,  h  JhB rJ - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53800' name='(Contributions Tax) drnwArn,  h  JhB rJ - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53900' name='(Insurance Policy Proceeds) drnwArn,  h  JhB rJ - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53920' name='(Life Insurance Premiums) drnwArn,  h  JhB rJ - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53940' name='(Income Protection Premiums) drnwArn,  h  JhB rJ - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53960' name='(Total and Permanent Disability Premiums) drnwArn,  h  JhB rJ - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53980' name='(Death Cover Premiums) drnwArn,  h  JhB rJ - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54000' name='(Management Fees) drnwArn,  h  JhB rJ - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54050' name='(Members Expenses) drnwArn,  h  JhB rJ - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54160' name='(Pensions Paid) drnwArn,  h  JhB rJ - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54500' name='(Benefits Paid/Transfers Out) drnwArn,  h  JhB rJ - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='55100' name='(Excess Contributions Tax) drnwArn,  h  JhB rJ - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='55700' name='(Superannuation Surcharge Tax) drnwArn,  h  JhB rJ - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='56100' name='(Internal Transfers In) drnwArn,  h  JhB rJ - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='57100' name='(Internal Transfers Out) drnwArn,  h  JhB rJ - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='58000' name='(Refund Excess Contributions) drnwArn,  h  JhB rJ - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='59100' name='(Anti-Detriment Reserve) drnwArn,  h  JhB rJ - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59300' name='(Investment Reserve) drnwArn,  h  JhB rJ - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59400' name='(Pension Reserve) drnwArn,  h  JhB rJ - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59500' name='(Self-Insurance Reserve) drnwArn,  h  JhB rJ - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='27500' name='(Proceeds from Insurance Policies) Aedrwdn, uuaanaurK s - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='28500' name='(Transfers In) Aedrwdn, uuaanaurK s - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39000' name='(Life Insurance Premiums) Aedrwdn, uuaanaurK s - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39300' name='(Life Insurance Premiums (Non Deductible)) Aedrwdn, uuaanaurK s - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39400' name='(Income Protection Premiums) Aedrwdn, uuaanaurK s - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39450' name='(Income Protection Premiums (Non Deductible)) Aedrwdn, uuaanaurK s - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39500' name='(Total and Permanent Disability Premiums) Aedrwdn, uuaanaurK s - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39550' name='(Total and Permanent Disability Premiums (Non Deductible)) Aedrwdn, uuaanaurK s - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39600' name='(Death Cover Premiums) Aedrwdn, uuaanaurK s - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39650' name='(Death Cover Premiums (Non Deductible)) Aedrwdn, uuaanaurK s - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='40000' name='(Management Fees) Aedrwdn, uuaanaurK s - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='40500' name='(Members Expenses) Aedrwdn, uuaanaurK s - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='41600' name='(Pensions Paid) Aedrwdn, uuaanaurK s - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='44000' name='(Excess Contributions Tax) Aedrwdn, uuaanaurK s - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='46000' name='(Benefits Paid/Transfers Out) Aedrwdn, uuaanaurK s - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='46600' name='(Refund Excess Contributions) Aedrwdn, uuaanaurK s - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='49300' name='(Writeback of Deferred Tax) Aedrwdn, uuaanaurK s - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='50010' name='(Opening Balance) Aedrwdn, uuaanaurK s - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='52850' name='(Transfers In) Aedrwdn, uuaanaurK s - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53100' name='(Share of Profit/(Loss)) Aedrwdn, uuaanaurK s - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53330' name='(Income Tax) Aedrwdn, uuaanaurK s - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53800' name='(Contributions Tax) Aedrwdn, uuaanaurK s - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53900' name='(Insurance Policy Proceeds) Aedrwdn, uuaanaurK s - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53920' name='(Life Insurance Premiums) Aedrwdn, uuaanaurK s - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53940' name='(Income Protection Premiums) Aedrwdn, uuaanaurK s - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53960' name='(Total and Permanent Disability Premiums) Aedrwdn, uuaanaurK s - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53980' name='(Death Cover Premiums) Aedrwdn, uuaanaurK s - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54000' name='(Management Fees) Aedrwdn, uuaanaurK s - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54050' name='(Members Expenses) Aedrwdn, uuaanaurK s - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54160' name='(Pensions Paid) Aedrwdn, uuaanaurK s - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54500' name='(Benefits Paid/Transfers Out) Aedrwdn, uuaanaurK s - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='55100' name='(Excess Contributions Tax) Aedrwdn, uuaanaurK s - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='55700' name='(Superannuation Surcharge Tax) Aedrwdn, uuaanaurK s - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='56100' name='(Internal Transfers In) Aedrwdn, uuaanaurK s - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='57100' name='(Internal Transfers Out) Aedrwdn, uuaanaurK s - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='58000' name='(Refund Excess Contributions) Aedrwdn, uuaanaurK s - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='59100' name='(Anti-Detriment Reserve) Aedrwdn, uuaanaurK s - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59300' name='(Investment Reserve) Aedrwdn, uuaanaurK s - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59400' name='(Pension Reserve) Aedrwdn, uuaanaurK s - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59500' name='(Self-Insurance Reserve) Aedrwdn, uuaanaurK s - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='27500' name='(Proceeds from Insurance Policies) Aedrwdn, uuaanaurK s - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='28500' name='(Transfers In) Aedrwdn, uuaanaurK s - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39000' name='(Life Insurance Premiums) Aedrwdn, uuaanaurK s - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39300' name='(Life Insurance Premiums (Non Deductible)) Aedrwdn, uuaanaurK s - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39400' name='(Income Protection Premiums) Aedrwdn, uuaanaurK s - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39450' name='(Income Protection Premiums (Non Deductible)) Aedrwdn, uuaanaurK s - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39500' name='(Total and Permanent Disability Premiums) Aedrwdn, uuaanaurK s - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39550' name='(Total and Permanent Disability Premiums (Non Deductible)) Aedrwdn, uuaanaurK s - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39600' name='(Death Cover Premiums) Aedrwdn, uuaanaurK s - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39650' name='(Death Cover Premiums (Non Deductible)) Aedrwdn, uuaanaurK s - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='40000' name='(Management Fees) Aedrwdn, uuaanaurK s - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='40500' name='(Members Expenses) Aedrwdn, uuaanaurK s - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='41600' name='(Pensions Paid) Aedrwdn, uuaanaurK s - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='44000' name='(Excess Contributions Tax) Aedrwdn, uuaanaurK s - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='46000' name='(Benefits Paid/Transfers Out) Aedrwdn, uuaanaurK s - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='46600' name='(Refund Excess Contributions) Aedrwdn, uuaanaurK s - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='49300' name='(Writeback of Deferred Tax) Aedrwdn, uuaanaurK s - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='50010' name='(Opening Balance) Aedrwdn, uuaanaurK s - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='52850' name='(Transfers In) Aedrwdn, uuaanaurK s - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53100' name='(Share of Profit/(Loss)) Aedrwdn, uuaanaurK s - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53330' name='(Income Tax) Aedrwdn, uuaanaurK s - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53800' name='(Contributions Tax) Aedrwdn, uuaanaurK s - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53900' name='(Insurance Policy Proceeds) Aedrwdn, uuaanaurK s - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53920' name='(Life Insurance Premiums) Aedrwdn, uuaanaurK s - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53940' name='(Income Protection Premiums) Aedrwdn, uuaanaurK s - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53960' name='(Total and Permanent Disability Premiums) Aedrwdn, uuaanaurK s - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53980' name='(Death Cover Premiums) Aedrwdn, uuaanaurK s - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54000' name='(Management Fees) Aedrwdn, uuaanaurK s - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54050' name='(Members Expenses) Aedrwdn, uuaanaurK s - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54160' name='(Pensions Paid) Aedrwdn, uuaanaurK s - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54500' name='(Benefits Paid/Transfers Out) Aedrwdn, uuaanaurK s - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='55100' name='(Excess Contributions Tax) Aedrwdn, uuaanaurK s - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='55700' name='(Superannuation Surcharge Tax) Aedrwdn, uuaanaurK s - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='56100' name='(Internal Transfers In) Aedrwdn, uuaanaurK s - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='57100' name='(Internal Transfers Out) Aedrwdn, uuaanaurK s - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='58000' name='(Refund Excess Contributions) Aedrwdn, uuaanaurK s - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='59100' name='(Anti-Detriment Reserve) Aedrwdn, uuaanaurK s - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59300' name='(Investment Reserve) Aedrwdn, uuaanaurK s - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59400' name='(Pension Reserve) Aedrwdn, uuaanaurK s - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59500' name='(Self-Insurance Reserve) Aedrwdn, uuaanaurK s - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='24200' name='(Contributions) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='27500' name='(Proceeds from Insurance Policies) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='28500' name='(Transfers In) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39000' name='(Life Insurance Premiums) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39300' name='(Life Insurance Premiums (Non Deductible)) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39400' name='(Income Protection Premiums) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39450' name='(Income Protection Premiums (Non Deductible)) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39500' name='(Total and Permanent Disability Premiums) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39550' name='(Total and Permanent Disability Premiums (Non Deductible)) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39600' name='(Death Cover Premiums) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39650' name='(Death Cover Premiums (Non Deductible)) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='40000' name='(Management Fees) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='40500' name='(Members Expenses) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='44000' name='(Excess Contributions Tax) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='46000' name='(Benefits Paid/Transfers Out) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='46600' name='(Refund Excess Contributions) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='48700' name='(Contributions Tax (Surcharge)) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='49300' name='(Writeback of Deferred Tax) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='50010' name='(Opening Balance) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='52420' name='(Contributions) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='52850' name='(Transfers In) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53100' name='(Share of Profit/(Loss)) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53330' name='(Income Tax) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53500' name='(No TFN Excess Contributions Tax) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53800' name='(Contributions Tax) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53900' name='(Insurance Policy Proceeds) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53920' name='(Life Insurance Premiums) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53940' name='(Income Protection Premiums) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53960' name='(Total and Permanent Disability Premiums) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53980' name='(Death Cover Premiums) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54000' name='(Management Fees) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54050' name='(Members Expenses) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54500' name='(Benefits Paid/Transfers Out) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='55100' name='(Excess Contributions Tax) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='55700' name='(Superannuation Surcharge Tax) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='56100' name='(Internal Transfers In) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='57100' name='(Internal Transfers Out) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='58000' name='(Refund Excess Contributions) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='59200' name='(Contribution Reserve) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59100' name='(Anti-Detriment Reserve) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59300' name='(Investment Reserve) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59400' name='(Pension Reserve) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59500' name='(Self-Insurance Reserve) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='27500' name='(Proceeds from Insurance Policies) drnwArn,  h  JhB rJ - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='28500' name='(Transfers In) drnwArn,  h  JhB rJ - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39000' name='(Life Insurance Premiums) drnwArn,  h  JhB rJ - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39300' name='(Life Insurance Premiums (Non Deductible)) drnwArn,  h  JhB rJ - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39400' name='(Income Protection Premiums) drnwArn,  h  JhB rJ - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39450' name='(Income Protection Premiums (Non Deductible)) drnwArn,  h  JhB rJ - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39500' name='(Total and Permanent Disability Premiums) drnwArn,  h  JhB rJ - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39550' name='(Total and Permanent Disability Premiums (Non Deductible)) drnwArn,  h  JhB rJ - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39600' name='(Death Cover Premiums) drnwArn,  h  JhB rJ - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39650' name='(Death Cover Premiums (Non Deductible)) drnwArn,  h  JhB rJ - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='40000' name='(Management Fees) drnwArn,  h  JhB rJ - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='40500' name='(Members Expenses) drnwArn,  h  JhB rJ - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='41600' name='(Pensions Paid) drnwArn,  h  JhB rJ - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='44000' name='(Excess Contributions Tax) drnwArn,  h  JhB rJ - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='46000' name='(Benefits Paid/Transfers Out) drnwArn,  h  JhB rJ - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='46600' name='(Refund Excess Contributions) drnwArn,  h  JhB rJ - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='49300' name='(Writeback of Deferred Tax) drnwArn,  h  JhB rJ - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='50010' name='(Opening Balance) drnwArn,  h  JhB rJ - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='52850' name='(Transfers In) drnwArn,  h  JhB rJ - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53100' name='(Share of Profit/(Loss)) drnwArn,  h  JhB rJ - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53330' name='(Income Tax) drnwArn,  h  JhB rJ - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53800' name='(Contributions Tax) drnwArn,  h  JhB rJ - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53900' name='(Insurance Policy Proceeds) drnwArn,  h  JhB rJ - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53920' name='(Life Insurance Premiums) drnwArn,  h  JhB rJ - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53940' name='(Income Protection Premiums) drnwArn,  h  JhB rJ - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53960' name='(Total and Permanent Disability Premiums) drnwArn,  h  JhB rJ - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53980' name='(Death Cover Premiums) drnwArn,  h  JhB rJ - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54000' name='(Management Fees) drnwArn,  h  JhB rJ - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54050' name='(Members Expenses) drnwArn,  h  JhB rJ - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54160' name='(Pensions Paid) drnwArn,  h  JhB rJ - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54500' name='(Benefits Paid/Transfers Out) drnwArn,  h  JhB rJ - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='55100' name='(Excess Contributions Tax) drnwArn,  h  JhB rJ - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='55700' name='(Superannuation Surcharge Tax) drnwArn,  h  JhB rJ - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='56100' name='(Internal Transfers In) drnwArn,  h  JhB rJ - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='57100' name='(Internal Transfers Out) drnwArn,  h  JhB rJ - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='58000' name='(Refund Excess Contributions) drnwArn,  h  JhB rJ - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='59100' name='(Anti-Detriment Reserve) drnwArn,  h  JhB rJ - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59300' name='(Investment Reserve) drnwArn,  h  JhB rJ - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59400' name='(Pension Reserve) drnwArn,  h  JhB rJ - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59500' name='(Self-Insurance Reserve) drnwArn,  h  JhB rJ - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='27500' name='(Proceeds from Insurance Policies) Aedrwdn, uuaanaurK s - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='28500' name='(Transfers In) Aedrwdn, uuaanaurK s - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39000' name='(Life Insurance Premiums) Aedrwdn, uuaanaurK s - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39300' name='(Life Insurance Premiums (Non Deductible)) Aedrwdn, uuaanaurK s - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39400' name='(Income Protection Premiums) Aedrwdn, uuaanaurK s - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39450' name='(Income Protection Premiums (Non Deductible)) Aedrwdn, uuaanaurK s - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39500' name='(Total and Permanent Disability Premiums) Aedrwdn, uuaanaurK s - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39550' name='(Total and Permanent Disability Premiums (Non Deductible)) Aedrwdn, uuaanaurK s - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39600' name='(Death Cover Premiums) Aedrwdn, uuaanaurK s - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39650' name='(Death Cover Premiums (Non Deductible)) Aedrwdn, uuaanaurK s - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='40000' name='(Management Fees) Aedrwdn, uuaanaurK s - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='40500' name='(Members Expenses) Aedrwdn, uuaanaurK s - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='41600' name='(Pensions Paid) Aedrwdn, uuaanaurK s - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='44000' name='(Excess Contributions Tax) Aedrwdn, uuaanaurK s - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='46000' name='(Benefits Paid/Transfers Out) Aedrwdn, uuaanaurK s - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='46600' name='(Refund Excess Contributions) Aedrwdn, uuaanaurK s - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='49300' name='(Writeback of Deferred Tax) Aedrwdn, uuaanaurK s - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='50010' name='(Opening Balance) Aedrwdn, uuaanaurK s - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='52850' name='(Transfers In) Aedrwdn, uuaanaurK s - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53100' name='(Share of Profit/(Loss)) Aedrwdn, uuaanaurK s - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53330' name='(Income Tax) Aedrwdn, uuaanaurK s - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53800' name='(Contributions Tax) Aedrwdn, uuaanaurK s - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53900' name='(Insurance Policy Proceeds) Aedrwdn, uuaanaurK s - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53920' name='(Life Insurance Premiums) Aedrwdn, uuaanaurK s - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53940' name='(Income Protection Premiums) Aedrwdn, uuaanaurK s - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53960' name='(Total and Permanent Disability Premiums) Aedrwdn, uuaanaurK s - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53980' name='(Death Cover Premiums) Aedrwdn, uuaanaurK s - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54000' name='(Management Fees) Aedrwdn, uuaanaurK s - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54050' name='(Members Expenses) Aedrwdn, uuaanaurK s - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54160' name='(Pensions Paid) Aedrwdn, uuaanaurK s - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54500' name='(Benefits Paid/Transfers Out) Aedrwdn, uuaanaurK s - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='55100' name='(Excess Contributions Tax) Aedrwdn, uuaanaurK s - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='55700' name='(Superannuation Surcharge Tax) Aedrwdn, uuaanaurK s - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='56100' name='(Internal Transfers In) Aedrwdn, uuaanaurK s - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='57100' name='(Internal Transfers Out) Aedrwdn, uuaanaurK s - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='58000' name='(Refund Excess Contributions) Aedrwdn, uuaanaurK s - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='59100' name='(Anti-Detriment Reserve) Aedrwdn, uuaanaurK s - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59300' name='(Investment Reserve) Aedrwdn, uuaanaurK s - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59400' name='(Pension Reserve) Aedrwdn, uuaanaurK s - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59500' name='(Self-Insurance Reserve) Aedrwdn, uuaanaurK s - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='27500' name='(Proceeds from Insurance Policies) drnwArn,  h  JhB rJ - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='28500' name='(Transfers In) drnwArn,  h  JhB rJ - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39000' name='(Life Insurance Premiums) drnwArn,  h  JhB rJ - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39300' name='(Life Insurance Premiums (Non Deductible)) drnwArn,  h  JhB rJ - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39400' name='(Income Protection Premiums) drnwArn,  h  JhB rJ - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39450' name='(Income Protection Premiums (Non Deductible)) drnwArn,  h  JhB rJ - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39500' name='(Total and Permanent Disability Premiums) drnwArn,  h  JhB rJ - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39550' name='(Total and Permanent Disability Premiums (Non Deductible)) drnwArn,  h  JhB rJ - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39600' name='(Death Cover Premiums) drnwArn,  h  JhB rJ - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39650' name='(Death Cover Premiums (Non Deductible)) drnwArn,  h  JhB rJ - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='40000' name='(Management Fees) drnwArn,  h  JhB rJ - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='40500' name='(Members Expenses) drnwArn,  h  JhB rJ - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='41600' name='(Pensions Paid) drnwArn,  h  JhB rJ - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='44000' name='(Excess Contributions Tax) drnwArn,  h  JhB rJ - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='46000' name='(Benefits Paid/Transfers Out) drnwArn,  h  JhB rJ - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='46600' name='(Refund Excess Contributions) drnwArn,  h  JhB rJ - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='49300' name='(Writeback of Deferred Tax) drnwArn,  h  JhB rJ - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='50010' name='(Opening Balance) drnwArn,  h  JhB rJ - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='52850' name='(Transfers In) drnwArn,  h  JhB rJ - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53100' name='(Share of Profit/(Loss)) drnwArn,  h  JhB rJ - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53330' name='(Income Tax) drnwArn,  h  JhB rJ - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53800' name='(Contributions Tax) drnwArn,  h  JhB rJ - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53900' name='(Insurance Policy Proceeds) drnwArn,  h  JhB rJ - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53920' name='(Life Insurance Premiums) drnwArn,  h  JhB rJ - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53940' name='(Income Protection Premiums) drnwArn,  h  JhB rJ - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53960' name='(Total and Permanent Disability Premiums) drnwArn,  h  JhB rJ - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53980' name='(Death Cover Premiums) drnwArn,  h  JhB rJ - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54000' name='(Management Fees) drnwArn,  h  JhB rJ - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54050' name='(Members Expenses) drnwArn,  h  JhB rJ - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54160' name='(Pensions Paid) drnwArn,  h  JhB rJ - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54500' name='(Benefits Paid/Transfers Out) drnwArn,  h  JhB rJ - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='55100' name='(Excess Contributions Tax) drnwArn,  h  JhB rJ - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='55700' name='(Superannuation Surcharge Tax) drnwArn,  h  JhB rJ - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='56100' name='(Internal Transfers In) drnwArn,  h  JhB rJ - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='57100' name='(Internal Transfers Out) drnwArn,  h  JhB rJ - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='58000' name='(Refund Excess Contributions) drnwArn,  h  JhB rJ - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='59100' name='(Anti-Detriment Reserve) drnwArn,  h  JhB rJ - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59300' name='(Investment Reserve) drnwArn,  h  JhB rJ - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59400' name='(Pension Reserve) drnwArn,  h  JhB rJ - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59500' name='(Self-Insurance Reserve) drnwArn,  h  JhB rJ - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='27500' name='(Proceeds from Insurance Policies) Aedrwdn, uuaanaurK s - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='28500' name='(Transfers In) Aedrwdn, uuaanaurK s - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39000' name='(Life Insurance Premiums) Aedrwdn, uuaanaurK s - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39300' name='(Life Insurance Premiums (Non Deductible)) Aedrwdn, uuaanaurK s - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39400' name='(Income Protection Premiums) Aedrwdn, uuaanaurK s - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39450' name='(Income Protection Premiums (Non Deductible)) Aedrwdn, uuaanaurK s - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39500' name='(Total and Permanent Disability Premiums) Aedrwdn, uuaanaurK s - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39550' name='(Total and Permanent Disability Premiums (Non Deductible)) Aedrwdn, uuaanaurK s - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39600' name='(Death Cover Premiums) Aedrwdn, uuaanaurK s - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39650' name='(Death Cover Premiums (Non Deductible)) Aedrwdn, uuaanaurK s - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='40000' name='(Management Fees) Aedrwdn, uuaanaurK s - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='40500' name='(Members Expenses) Aedrwdn, uuaanaurK s - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='41600' name='(Pensions Paid) Aedrwdn, uuaanaurK s - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='44000' name='(Excess Contributions Tax) Aedrwdn, uuaanaurK s - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='46000' name='(Benefits Paid/Transfers Out) Aedrwdn, uuaanaurK s - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='46600' name='(Refund Excess Contributions) Aedrwdn, uuaanaurK s - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='49300' name='(Writeback of Deferred Tax) Aedrwdn, uuaanaurK s - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='50010' name='(Opening Balance) Aedrwdn, uuaanaurK s - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='52850' name='(Transfers In) Aedrwdn, uuaanaurK s - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53100' name='(Share of Profit/(Loss)) Aedrwdn, uuaanaurK s - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53330' name='(Income Tax) Aedrwdn, uuaanaurK s - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53800' name='(Contributions Tax) Aedrwdn, uuaanaurK s - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53900' name='(Insurance Policy Proceeds) Aedrwdn, uuaanaurK s - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53920' name='(Life Insurance Premiums) Aedrwdn, uuaanaurK s - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53940' name='(Income Protection Premiums) Aedrwdn, uuaanaurK s - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53960' name='(Total and Permanent Disability Premiums) Aedrwdn, uuaanaurK s - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53980' name='(Death Cover Premiums) Aedrwdn, uuaanaurK s - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54000' name='(Management Fees) Aedrwdn, uuaanaurK s - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54050' name='(Members Expenses) Aedrwdn, uuaanaurK s - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54160' name='(Pensions Paid) Aedrwdn, uuaanaurK s - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54500' name='(Benefits Paid/Transfers Out) Aedrwdn, uuaanaurK s - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='55100' name='(Excess Contributions Tax) Aedrwdn, uuaanaurK s - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='55700' name='(Superannuation Surcharge Tax) Aedrwdn, uuaanaurK s - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='56100' name='(Internal Transfers In) Aedrwdn, uuaanaurK s - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='57100' name='(Internal Transfers Out) Aedrwdn, uuaanaurK s - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='58000' name='(Refund Excess Contributions) Aedrwdn, uuaanaurK s - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='59100' name='(Anti-Detriment Reserve) Aedrwdn, uuaanaurK s - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59300' name='(Investment Reserve) Aedrwdn, uuaanaurK s - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59400' name='(Pension Reserve) Aedrwdn, uuaanaurK s - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59500' name='(Self-Insurance Reserve) Aedrwdn, uuaanaurK s - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='27500' name='(Proceeds from Insurance Policies) drnwArn,  h  JhB rJ - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='28500' name='(Transfers In) drnwArn,  h  JhB rJ - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39000' name='(Life Insurance Premiums) drnwArn,  h  JhB rJ - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39300' name='(Life Insurance Premiums (Non Deductible)) drnwArn,  h  JhB rJ - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39400' name='(Income Protection Premiums) drnwArn,  h  JhB rJ - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39450' name='(Income Protection Premiums (Non Deductible)) drnwArn,  h  JhB rJ - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39500' name='(Total and Permanent Disability Premiums) drnwArn,  h  JhB rJ - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39550' name='(Total and Permanent Disability Premiums (Non Deductible)) drnwArn,  h  JhB rJ - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39600' name='(Death Cover Premiums) drnwArn,  h  JhB rJ - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39650' name='(Death Cover Premiums (Non Deductible)) drnwArn,  h  JhB rJ - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='40000' name='(Management Fees) drnwArn,  h  JhB rJ - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='40500' name='(Members Expenses) drnwArn,  h  JhB rJ - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='41600' name='(Pensions Paid) drnwArn,  h  JhB rJ - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='44000' name='(Excess Contributions Tax) drnwArn,  h  JhB rJ - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='46000' name='(Benefits Paid/Transfers Out) drnwArn,  h  JhB rJ - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='46600' name='(Refund Excess Contributions) drnwArn,  h  JhB rJ - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='49300' name='(Writeback of Deferred Tax) drnwArn,  h  JhB rJ - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='50010' name='(Opening Balance) drnwArn,  h  JhB rJ - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='52850' name='(Transfers In) drnwArn,  h  JhB rJ - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53100' name='(Share of Profit/(Loss)) drnwArn,  h  JhB rJ - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53330' name='(Income Tax) drnwArn,  h  JhB rJ - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53800' name='(Contributions Tax) drnwArn,  h  JhB rJ - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53900' name='(Insurance Policy Proceeds) drnwArn,  h  JhB rJ - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53920' name='(Life Insurance Premiums) drnwArn,  h  JhB rJ - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53940' name='(Income Protection Premiums) drnwArn,  h  JhB rJ - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53960' name='(Total and Permanent Disability Premiums) drnwArn,  h  JhB rJ - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53980' name='(Death Cover Premiums) drnwArn,  h  JhB rJ - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54000' name='(Management Fees) drnwArn,  h  JhB rJ - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54050' name='(Members Expenses) drnwArn,  h  JhB rJ - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54160' name='(Pensions Paid) drnwArn,  h  JhB rJ - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54500' name='(Benefits Paid/Transfers Out) drnwArn,  h  JhB rJ - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='55100' name='(Excess Contributions Tax) drnwArn,  h  JhB rJ - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='55700' name='(Superannuation Surcharge Tax) drnwArn,  h  JhB rJ - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='56100' name='(Internal Transfers In) drnwArn,  h  JhB rJ - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='57100' name='(Internal Transfers Out) drnwArn,  h  JhB rJ - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='58000' name='(Refund Excess Contributions) drnwArn,  h  JhB rJ - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='59100' name='(Anti-Detriment Reserve) drnwArn,  h  JhB rJ - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59300' name='(Investment Reserve) drnwArn,  h  JhB rJ - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59400' name='(Pension Reserve) drnwArn,  h  JhB rJ - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59500' name='(Self-Insurance Reserve) drnwArn,  h  JhB rJ - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='27500' name='(Proceeds from Insurance Policies) Aedrwdn, uuaanaurK s - Pension (ABP 5)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='28500' name='(Transfers In) Aedrwdn, uuaanaurK s - Pension (ABP 5)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39000' name='(Life Insurance Premiums) Aedrwdn, uuaanaurK s - Pension (ABP 5)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39300' name='(Life Insurance Premiums (Non Deductible)) Aedrwdn, uuaanaurK s - Pension (ABP 5)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39400' name='(Income Protection Premiums) Aedrwdn, uuaanaurK s - Pension (ABP 5)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39450' name='(Income Protection Premiums (Non Deductible)) Aedrwdn, uuaanaurK s - Pension (ABP 5)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39500' name='(Total and Permanent Disability Premiums) Aedrwdn, uuaanaurK s - Pension (ABP 5)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39550' name='(Total and Permanent Disability Premiums (Non Deductible)) Aedrwdn, uuaanaurK s - Pension (ABP 5)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39600' name='(Death Cover Premiums) Aedrwdn, uuaanaurK s - Pension (ABP 5)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39650' name='(Death Cover Premiums (Non Deductible)) Aedrwdn, uuaanaurK s - Pension (ABP 5)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='40000' name='(Management Fees) Aedrwdn, uuaanaurK s - Pension (ABP 5)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='40500' name='(Members Expenses) Aedrwdn, uuaanaurK s - Pension (ABP 5)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='41600' name='(Pensions Paid) Aedrwdn, uuaanaurK s - Pension (ABP 5)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='44000' name='(Excess Contributions Tax) Aedrwdn, uuaanaurK s - Pension (ABP 5)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='46000' name='(Benefits Paid/Transfers Out) Aedrwdn, uuaanaurK s - Pension (ABP 5)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='46600' name='(Refund Excess Contributions) Aedrwdn, uuaanaurK s - Pension (ABP 5)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='49300' name='(Writeback of Deferred Tax) Aedrwdn, uuaanaurK s - Pension (ABP 5)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='50010' name='(Opening Balance) Aedrwdn, uuaanaurK s - Pension (ABP 5)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='52850' name='(Transfers In) Aedrwdn, uuaanaurK s - Pension (ABP 5)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53100' name='(Share of Profit/(Loss)) Aedrwdn, uuaanaurK s - Pension (ABP 5)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53330' name='(Income Tax) Aedrwdn, uuaanaurK s - Pension (ABP 5)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53800' name='(Contributions Tax) Aedrwdn, uuaanaurK s - Pension (ABP 5)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53900' name='(Insurance Policy Proceeds) Aedrwdn, uuaanaurK s - Pension (ABP 5)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53920' name='(Life Insurance Premiums) Aedrwdn, uuaanaurK s - Pension (ABP 5)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53940' name='(Income Protection Premiums) Aedrwdn, uuaanaurK s - Pension (ABP 5)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53960' name='(Total and Permanent Disability Premiums) Aedrwdn, uuaanaurK s - Pension (ABP 5)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53980' name='(Death Cover Premiums) Aedrwdn, uuaanaurK s - Pension (ABP 5)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54000' name='(Management Fees) Aedrwdn, uuaanaurK s - Pension (ABP 5)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54050' name='(Members Expenses) Aedrwdn, uuaanaurK s - Pension (ABP 5)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54160' name='(Pensions Paid) Aedrwdn, uuaanaurK s - Pension (ABP 5)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54500' name='(Benefits Paid/Transfers Out) Aedrwdn, uuaanaurK s - Pension (ABP 5)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='55100' name='(Excess Contributions Tax) Aedrwdn, uuaanaurK s - Pension (ABP 5)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='55700' name='(Superannuation Surcharge Tax) Aedrwdn, uuaanaurK s - Pension (ABP 5)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='56100' name='(Internal Transfers In) Aedrwdn, uuaanaurK s - Pension (ABP 5)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='57100' name='(Internal Transfers Out) Aedrwdn, uuaanaurK s - Pension (ABP 5)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='58000' name='(Refund Excess Contributions) Aedrwdn, uuaanaurK s - Pension (ABP 5)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='59100' name='(Anti-Detriment Reserve) Aedrwdn, uuaanaurK s - Pension (ABP 5)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59300' name='(Investment Reserve) Aedrwdn, uuaanaurK s - Pension (ABP 5)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59400' name='(Pension Reserve) Aedrwdn, uuaanaurK s - Pension (ABP 5)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59500' name='(Self-Insurance Reserve) Aedrwdn, uuaanaurK s - Pension (ABP 5)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='24200' name='(Contributions) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='27500' name='(Proceeds from Insurance Policies) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='28500' name='(Transfers In) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39000' name='(Life Insurance Premiums) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39300' name='(Life Insurance Premiums (Non Deductible)) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39400' name='(Income Protection Premiums) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39450' name='(Income Protection Premiums (Non Deductible)) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39500' name='(Total and Permanent Disability Premiums) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39550' name='(Total and Permanent Disability Premiums (Non Deductible)) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39600' name='(Death Cover Premiums) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39650' name='(Death Cover Premiums (Non Deductible)) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='40000' name='(Management Fees) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='40500' name='(Members Expenses) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='44000' name='(Excess Contributions Tax) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='46000' name='(Benefits Paid/Transfers Out) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='46600' name='(Refund Excess Contributions) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='48700' name='(Contributions Tax (Surcharge)) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='49300' name='(Writeback of Deferred Tax) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='50010' name='(Opening Balance) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='52420' name='(Contributions) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='52850' name='(Transfers In) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53100' name='(Share of Profit/(Loss)) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53330' name='(Income Tax) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53500' name='(No TFN Excess Contributions Tax) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53800' name='(Contributions Tax) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53900' name='(Insurance Policy Proceeds) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53920' name='(Life Insurance Premiums) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53940' name='(Income Protection Premiums) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53960' name='(Total and Permanent Disability Premiums) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53980' name='(Death Cover Premiums) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54000' name='(Management Fees) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54050' name='(Members Expenses) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54500' name='(Benefits Paid/Transfers Out) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='55100' name='(Excess Contributions Tax) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='55700' name='(Superannuation Surcharge Tax) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='56100' name='(Internal Transfers In) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='57100' name='(Internal Transfers Out) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='58000' name='(Refund Excess Contributions) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='59200' name='(Contribution Reserve) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59100' name='(Anti-Detriment Reserve) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59300' name='(Investment Reserve) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59400' name='(Pension Reserve) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59500' name='(Self-Insurance Reserve) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='24200' name='(Contributions) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='27500' name='(Proceeds from Insurance Policies) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='28500' name='(Transfers In) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39000' name='(Life Insurance Premiums) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39300' name='(Life Insurance Premiums (Non Deductible)) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39400' name='(Income Protection Premiums) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39450' name='(Income Protection Premiums (Non Deductible)) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39500' name='(Total and Permanent Disability Premiums) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39550' name='(Total and Permanent Disability Premiums (Non Deductible)) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39600' name='(Death Cover Premiums) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='39650' name='(Death Cover Premiums (Non Deductible)) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='40000' name='(Management Fees) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='40500' name='(Members Expenses) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='44000' name='(Excess Contributions Tax) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='46000' name='(Benefits Paid/Transfers Out) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='46600' name='(Refund Excess Contributions) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='48700' name='(Contributions Tax (Surcharge)) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='49300' name='(Writeback of Deferred Tax) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='50010' name='(Opening Balance) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='52420' name='(Contributions) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='52850' name='(Transfers In) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53100' name='(Share of Profit/(Loss)) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53330' name='(Income Tax) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53500' name='(No TFN Excess Contributions Tax) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53800' name='(Contributions Tax) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53900' name='(Insurance Policy Proceeds) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53920' name='(Life Insurance Premiums) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53940' name='(Income Protection Premiums) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53960' name='(Total and Permanent Disability Premiums) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='53980' name='(Death Cover Premiums) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54000' name='(Management Fees) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54050' name='(Members Expenses) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='54500' name='(Benefits Paid/Transfers Out) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='55100' name='(Excess Contributions Tax) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='55700' name='(Superannuation Surcharge Tax) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='56100' name='(Internal Transfers In) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='57100' name='(Internal Transfers Out) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='58000' name='(Refund Excess Contributions) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='59200' name='(Contribution Reserve) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59100' name='(Anti-Detriment Reserve) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59300' name='(Investment Reserve) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59400' name='(Pension Reserve) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='59500' name='(Self-Insurance Reserve) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='83000' name='Challenge Cash Management Account' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='26500' name='Challenge Cash Management Account' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='37500' name='Challenge Cash Management Account' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='25000' name='Challenge Cash Management Account' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='60400' name='Challenge Cash Management Account' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset - Bank, minCode=60400, maxCode=60800}' />
	< code='83000' name='Hartley Poynton' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='26500' name='Hartley Poynton' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='37500' name='Hartley Poynton' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='25000' name='Hartley Poynton' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='60400' name='Hartley Poynton' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset - Bank, minCode=60400, maxCode=60800}' />
	< code='83000' name='Westpac Business Flexi 27-0988' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='26500' name='Westpac Business Flexi 27-0988' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='37500' name='Westpac Business Flexi 27-0988' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='25000' name='Westpac Business Flexi 27-0988' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='60400' name='Westpac Business Flexi 27-0988' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset - Bank, minCode=60400, maxCode=60800}' />
	< code='83000' name='Andrews SF share transactions account' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='26500' name='Andrews SF share transactions account' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='37500' name='Andrews SF share transactions account' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='25000' name='Andrews SF share transactions account' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='60400' name='Andrews SF share transactions account' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset - Bank, minCode=60400, maxCode=60800}' />
	< code='83000' name='Westpac Business Cash Reserve 16-0105' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='26500' name='Westpac Business Cash Reserve 16-0105' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='37500' name='Westpac Business Cash Reserve 16-0105' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='25000' name='Westpac Business Cash Reserve 16-0105' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='60400' name='Westpac Business Cash Reserve 16-0105' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset - Bank, minCode=60400, maxCode=60800}' />
	< code='83000' name='Challenge Bank Term Deposit 420341' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='26500' name='Challenge Bank Term Deposit 420341' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='37500' name='Challenge Bank Term Deposit 420341' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='25000' name='Challenge Bank Term Deposit 420341' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='60400' name='Challenge Bank Term Deposit 420341' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset - Bank, minCode=60400, maxCode=60800}' />
	< code='83000' name='Macquarie CMT Account' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='26500' name='Macquarie CMT Account' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='37500' name='Macquarie CMT Account' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='25000' name='Macquarie CMT Account' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='60400' name='Macquarie CMT Account' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset - Bank, minCode=60400, maxCode=60800}' />
	< code='83000' name='Westpac Term Deposit 160308 (Matures 11/12/10)' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='26500' name='Westpac Term Deposit 160308 (Matures 11/12/10)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='37500' name='Westpac Term Deposit 160308 (Matures 11/12/10)' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='25000' name='Westpac Term Deposit 160308 (Matures 11/12/10)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='60400' name='Westpac Term Deposit 160308 (Matures 11/12/10)' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset - Bank, minCode=60400, maxCode=60800}' />
	< code='83000' name='Westpac Term Deposit 164325 (Matures 25/03/15)' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='26500' name='Westpac Term Deposit 164325 (Matures 25/03/15)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='37500' name='Westpac Term Deposit 164325 (Matures 25/03/15)' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='25000' name='Westpac Term Deposit 164325 (Matures 25/03/15)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='60400' name='Westpac Term Deposit 164325 (Matures 25/03/15)' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset - Bank, minCode=60400, maxCode=60800}' />
	< code='83000' name='Westpac Term Deposit 170346' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='26500' name='Westpac Term Deposit 170346' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='37500' name='Westpac Term Deposit 170346' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='25000' name='Westpac Term Deposit 170346' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='60400' name='Westpac Term Deposit 170346' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset - Bank, minCode=60400, maxCode=60800}' />
	< code='83000' name='Westpac Term Deposit 173467' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='26500' name='Westpac Term Deposit 173467' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='37500' name='Westpac Term Deposit 173467' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='25000' name='Westpac Term Deposit 173467' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='60400' name='Westpac Term Deposit 173467' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset - Bank, minCode=60400, maxCode=60800}' />
	< code='83000' name='Westpac Term Deposit 173475' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='26500' name='Westpac Term Deposit 173475' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='37500' name='Westpac Term Deposit 173475' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='25000' name='Westpac Term Deposit 173475' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='60400' name='Westpac Term Deposit 173475' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset - Bank, minCode=60400, maxCode=60800}' />
	< code='83000' name='Westpac Term Deposit 173870' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='26500' name='Westpac Term Deposit 173870' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='37500' name='Westpac Term Deposit 173870' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='25000' name='Westpac Term Deposit 173870' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='60400' name='Westpac Term Deposit 173870' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset - Bank, minCode=60400, maxCode=60800}' />
	< code='83000' name='NAB Term Deposit 11-566-4704' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='26500' name='NAB Term Deposit 11-566-4704' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='37500' name='NAB Term Deposit 11-566-4704' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='25000' name='NAB Term Deposit 11-566-4704' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='60400' name='NAB Term Deposit 11-566-4704' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset - Bank, minCode=60400, maxCode=60800}' />
	< code='83000' name='NAB Term Deposit 12-914-8292' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='26500' name='NAB Term Deposit 12-914-8292' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='37500' name='NAB Term Deposit 12-914-8292' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='25000' name='NAB Term Deposit 12-914-8292' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='60400' name='NAB Term Deposit 12-914-8292' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset - Bank, minCode=60400, maxCode=60800}' />
	< code='83000' name='NAB Term Deposit 11-647-3782' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='26500' name='NAB Term Deposit 11-647-3782' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='37500' name='NAB Term Deposit 11-647-3782' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='25000' name='NAB Term Deposit 11-647-3782' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='60400' name='NAB Term Deposit 11-647-3782' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset - Bank, minCode=60400, maxCode=60800}' />
	< code='37500' name='ATO' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='25000' name='ATO' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='ATO' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='26500' name='ATO' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='76000' name='ATO' accountClass='Sub Account' securityId='68385753' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='65000' name='Athena Finance Pty Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='25000' name='Athena Finance Pty Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='81000' name='Athena Finance Pty Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='83000' name='Athena Finance Pty Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='37500' name='Athena Finance Pty Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='72450' name='Athena Finance Pty Ltd' accountClass='Sub Account' securityId='68385676' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='37500' name='21.41oz Unallocated Gold' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='25000' name='21.41oz Unallocated Gold' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='21.41oz Unallocated Gold' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='26500' name='21.41oz Unallocated Gold' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='76000' name='21.41oz Unallocated Gold' accountClass='Sub Account' securityId='68385677' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='27850' name='Pioneer Water Tank (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='28000' name='Pioneer Water Tank (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='25500' name='Pioneer Water Tank (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='27800' name='Pioneer Water Tank (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='37500' name='Pioneer Water Tank (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='33400' name='Pioneer Water Tank (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='83000' name='Pioneer Water Tank (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='76550' name='Pioneer Water Tank (Carter Road)' accountClass='Sub Account' securityId='68385681' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='27850' name='Rainwater Tank (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='28000' name='Rainwater Tank (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='25500' name='Rainwater Tank (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='27800' name='Rainwater Tank (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='37500' name='Rainwater Tank (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='33400' name='Rainwater Tank (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='83000' name='Rainwater Tank (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='76550' name='Rainwater Tank (Carter Road)' accountClass='Sub Account' securityId='68385682' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='27850' name='Bore Pump (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='28000' name='Bore Pump (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='25500' name='Bore Pump (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='27800' name='Bore Pump (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='37500' name='Bore Pump (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='33400' name='Bore Pump (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='83000' name='Bore Pump (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='76550' name='Bore Pump (Carter Road)' accountClass='Sub Account' securityId='68385683' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='27800' name='Cattle Yards Fencing (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='25500' name='Cattle Yards Fencing (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='28000' name='Cattle Yards Fencing (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='33400' name='Cattle Yards Fencing (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='37500' name='Cattle Yards Fencing (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='27850' name='Cattle Yards Fencing (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Cattle Yards Fencing (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='76500' name='Cattle Yards Fencing (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='41950' name='Lot 4, Carters Road, Margaret River' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='41990' name='Lot 4, Carters Road, Margaret River' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42120' name='Lot 4, Carters Road, Margaret River' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='41960' name='Lot 4, Carters Road, Margaret River' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42150' name='Lot 4, Carters Road, Margaret River' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42030' name='Lot 4, Carters Road, Margaret River' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42000' name='Lot 4, Carters Road, Margaret River' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42140' name='Lot 4, Carters Road, Margaret River' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='41970' name='Lot 4, Carters Road, Margaret River' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='37500' name='Lot 4, Carters Road, Margaret River' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42080' name='Lot 4, Carters Road, Margaret River' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42060' name='Lot 4, Carters Road, Margaret River' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='41980' name='Lot 4, Carters Road, Margaret River' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42050' name='Lot 4, Carters Road, Margaret River' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='28000' name='Lot 4, Carters Road, Margaret River' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='42070' name='Lot 4, Carters Road, Margaret River' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='41940' name='Lot 4, Carters Road, Margaret River' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='41930' name='Lot 4, Carters Road, Margaret River' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='33400' name='Lot 4, Carters Road, Margaret River' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42130' name='Lot 4, Carters Road, Margaret River' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='83000' name='Lot 4, Carters Road, Margaret River' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='42110' name='Lot 4, Carters Road, Margaret River' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42100' name='Lot 4, Carters Road, Margaret River' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42090' name='Lot 4, Carters Road, Margaret River' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42020' name='Lot 4, Carters Road, Margaret River' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='41920' name='Lot 4, Carters Road, Margaret River' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42040' name='Lot 4, Carters Road, Margaret River' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42010' name='Lot 4, Carters Road, Margaret River' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='77200' name='Lot 4, Carters Road, Margaret River' accountClass='Sub Account' securityId='68385684' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='41950' name='Capital Improvement - Carters Rd Farm' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='41990' name='Capital Improvement - Carters Rd Farm' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42120' name='Capital Improvement - Carters Rd Farm' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='41960' name='Capital Improvement - Carters Rd Farm' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42150' name='Capital Improvement - Carters Rd Farm' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42030' name='Capital Improvement - Carters Rd Farm' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42000' name='Capital Improvement - Carters Rd Farm' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42140' name='Capital Improvement - Carters Rd Farm' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='41970' name='Capital Improvement - Carters Rd Farm' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='37500' name='Capital Improvement - Carters Rd Farm' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42080' name='Capital Improvement - Carters Rd Farm' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42060' name='Capital Improvement - Carters Rd Farm' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='41980' name='Capital Improvement - Carters Rd Farm' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42050' name='Capital Improvement - Carters Rd Farm' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='28000' name='Capital Improvement - Carters Rd Farm' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='42070' name='Capital Improvement - Carters Rd Farm' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='41940' name='Capital Improvement - Carters Rd Farm' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='41930' name='Capital Improvement - Carters Rd Farm' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='33400' name='Capital Improvement - Carters Rd Farm' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42130' name='Capital Improvement - Carters Rd Farm' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='83000' name='Capital Improvement - Carters Rd Farm' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='42110' name='Capital Improvement - Carters Rd Farm' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42100' name='Capital Improvement - Carters Rd Farm' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42090' name='Capital Improvement - Carters Rd Farm' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42020' name='Capital Improvement - Carters Rd Farm' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='41920' name='Capital Improvement - Carters Rd Farm' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42040' name='Capital Improvement - Carters Rd Farm' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='42010' name='Capital Improvement - Carters Rd Farm' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='77200' name='Capital Improvement - Carters Rd Farm' accountClass='Sub Account' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Autron Corporation Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Autron Corporation Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Autron Corporation Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Autron Corporation Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Autron Corporation Ltd' accountClass='Sub Account' securityId='723333' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Coles Myer Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Coles Myer Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Coles Myer Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Coles Myer Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Coles Myer Limited' accountClass='Sub Account' securityId='68385685' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Cable&amp;wireless Optus' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Cable&amp;wireless Optus' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Cable&amp;wireless Optus' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Cable&amp;wireless Optus' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Cable&amp;wireless Optus' accountClass='Sub Account' securityId='68385599' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Ecorp Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Ecorp Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Ecorp Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Ecorp Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Ecorp Limited' accountClass='Sub Account' securityId='68385601' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Etrade Australia' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Etrade Australia' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Etrade Australia' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Etrade Australia' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Etrade Australia' accountClass='Sub Account' securityId='68385686' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Healthscope Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Healthscope Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Healthscope Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Healthscope Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Healthscope Limited' accountClass='Sub Account' securityId='843396' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='International Contract Manufact.' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='International Contract Manufact.' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='International Contract Manufact.' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='International Contract Manufact.' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='International Contract Manufact.' accountClass='Sub Account' securityId='68385687' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='IXLA Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='IXLA Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='IXLA Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='IXLA Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='IXLA Limited' accountClass='Sub Account' securityId='68385688' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Normandy Mining' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Normandy Mining' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Normandy Mining' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Normandy Mining' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Normandy Mining' accountClass='Sub Account' securityId='68385689' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Precious Metals-Options exp.30/06/01' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Precious Metals-Options exp.30/06/01' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Precious Metals-Options exp.30/06/01' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Precious Metals-Options exp.30/06/01' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Precious Metals-Options exp.30/06/01' accountClass='Sub Account' securityId='68385690' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='West Australian News' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='West Australian News' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='West Australian News' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='West Australian News' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='West Australian News' accountClass='Sub Account' securityId='837526' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Westpac Banking Corp' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Westpac Banking Corp' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Westpac Banking Corp' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Westpac Banking Corp' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Westpac Banking Corp' accountClass='Sub Account' securityId='701417' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='FTR Holdings Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='FTR Holdings Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='FTR Holdings Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='FTR Holdings Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='FTR Holdings Limited' accountClass='Sub Account' securityId='68385691' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='FXF Trust' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='FXF Trust' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='FXF Trust' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='FXF Trust' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='FXF Trust' accountClass='Sub Account' securityId='68385692' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Securenet Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Securenet Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Securenet Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Securenet Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Securenet Limited' accountClass='Sub Account' securityId='68385693' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Reckon Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Reckon Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Reckon Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Reckon Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Reckon Limited' accountClass='Sub Account' securityId='695995' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Burdekin Pacific' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Burdekin Pacific' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Burdekin Pacific' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Burdekin Pacific' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Burdekin Pacific' accountClass='Sub Account' securityId='68385694' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Mayne Group Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Mayne Group Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Mayne Group Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Mayne Group Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Mayne Group Ltd' accountClass='Sub Account' securityId='68385695' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Australian Stock Exchange Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Australian Stock Exchange Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Australian Stock Exchange Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Australian Stock Exchange Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Australian Stock Exchange Ltd' accountClass='Sub Account' securityId='707319' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Amp Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Amp Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Amp Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Amp Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Amp Limited' accountClass='Sub Account' securityId='681544' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Qantas Airways' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Qantas Airways' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Qantas Airways' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Qantas Airways' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Qantas Airways' accountClass='Sub Account' securityId='678883' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Colorado Group' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Colorado Group' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Colorado Group' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Colorado Group' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Colorado Group' accountClass='Sub Account' securityId='68385696' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Telstra Corporation Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Telstra Corporation Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Telstra Corporation Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Telstra Corporation Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Telstra Corporation Ltd' accountClass='Sub Account' securityId='687013' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Santos Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Santos Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Santos Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Santos Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Santos Ltd' accountClass='Sub Account' securityId='723353' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Southcorp Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Southcorp Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Southcorp Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Southcorp Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Southcorp Limited' accountClass='Sub Account' securityId='68385697' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Toll Holdings Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Toll Holdings Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Toll Holdings Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Toll Holdings Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Toll Holdings Ltd' accountClass='Sub Account' securityId='698677' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Michelago Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Michelago Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Michelago Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Michelago Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Michelago Limited' accountClass='Sub Account' securityId='68385698' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Pahth Telecom.' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Pahth Telecom.' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Pahth Telecom.' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Pahth Telecom.' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Pahth Telecom.' accountClass='Sub Account' securityId='68385699' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Resolute Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Resolute Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Resolute Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Resolute Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Resolute Limited' accountClass='Sub Account' securityId='698748' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Finders Gold' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Finders Gold' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Finders Gold' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Finders Gold' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Finders Gold' accountClass='Sub Account' securityId='68385700' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Australia and NZ Banking Group' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Australia and NZ Banking Group' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Australia and NZ Banking Group' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Australia and NZ Banking Group' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Australia and NZ Banking Group' accountClass='Sub Account' securityId='728641' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Macquarie Corporate' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Macquarie Corporate' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Macquarie Corporate' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Macquarie Corporate' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Macquarie Corporate' accountClass='Sub Account' securityId='723747' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Programmed Maintenance Services' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Programmed Maintenance Services' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Programmed Maintenance Services' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Programmed Maintenance Services' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Programmed Maintenance Services' accountClass='Sub Account' securityId='695554' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Orica Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Orica Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Orica Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Orica Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Orica Limited' accountClass='Sub Account' securityId='728916' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Eisa Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Eisa Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Eisa Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Eisa Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Eisa Limited' accountClass='Sub Account' securityId='68385701' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Paladin Resources' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Paladin Resources' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Paladin Resources' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Paladin Resources' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Paladin Resources' accountClass='Sub Account' securityId='703365' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='DCS Technologies' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='DCS Technologies' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='DCS Technologies' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='DCS Technologies' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='DCS Technologies' accountClass='Sub Account' securityId='68385702' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Greater Pacific Gold' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Greater Pacific Gold' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Greater Pacific Gold' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Greater Pacific Gold' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Greater Pacific Gold' accountClass='Sub Account' securityId='68385703' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Goodman Fielder' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Goodman Fielder' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Goodman Fielder' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Goodman Fielder' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Goodman Fielder' accountClass='Sub Account' securityId='68385704' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Novogen Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Novogen Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Novogen Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Novogen Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Novogen Limited' accountClass='Sub Account' securityId='724805' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Cellnet Telecom.' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Cellnet Telecom.' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Cellnet Telecom.' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Cellnet Telecom.' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Cellnet Telecom.' accountClass='Sub Account' securityId='689239' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Argosy Minerals Inc' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Argosy Minerals Inc' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Argosy Minerals Inc' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Argosy Minerals Inc' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Argosy Minerals Inc' accountClass='Sub Account' securityId='728297' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Insurance My Way' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Insurance My Way' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Insurance My Way' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Insurance My Way' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Insurance My Way' accountClass='Sub Account' securityId='68385705' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Davnet Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Davnet Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Davnet Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Davnet Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Davnet Limited' accountClass='Sub Account' securityId='68385606' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Capral Aluminium' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Capral Aluminium' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Capral Aluminium' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Capral Aluminium' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Capral Aluminium' accountClass='Sub Account' securityId='722816' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Wmc Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Wmc Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Wmc Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Wmc Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Wmc Limited' accountClass='Sub Account' securityId='68385590' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Lend Lease Corp.' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Lend Lease Corp.' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Lend Lease Corp.' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Lend Lease Corp.' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Lend Lease Corp.' accountClass='Sub Account' securityId='696618' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='M.I.M. Holdings Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='M.I.M. Holdings Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='M.I.M. Holdings Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='M.I.M. Holdings Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='M.I.M. Holdings Ltd' accountClass='Sub Account' securityId='68385706' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Woodside Petroleum' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Woodside Petroleum' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Woodside Petroleum' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Woodside Petroleum' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Woodside Petroleum' accountClass='Sub Account' securityId='710344' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Futuris Corporation' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Futuris Corporation' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Futuris Corporation' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Futuris Corporation' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Futuris Corporation' accountClass='Sub Account' securityId='68385707' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Iluka Resources' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Iluka Resources' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Iluka Resources' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Iluka Resources' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Iluka Resources' accountClass='Sub Account' securityId='730832' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Chemeq Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Chemeq Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Chemeq Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Chemeq Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Chemeq Limited' accountClass='Sub Account' securityId='831709' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='New Tel Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='New Tel Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='New Tel Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='New Tel Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='New Tel Limited' accountClass='Sub Account' securityId='68385708' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='National Aust. Bank' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='National Aust. Bank' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='National Aust. Bank' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='National Aust. Bank' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='National Aust. Bank' accountClass='Sub Account' securityId='731230' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Techniche Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Techniche Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Techniche Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Techniche Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Techniche Limited' accountClass='Sub Account' securityId='68385709' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Sausage Software' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Sausage Software' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Sausage Software' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Sausage Software' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Sausage Software' accountClass='Sub Account' securityId='68385710' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Solution 6 Holdings' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Solution 6 Holdings' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Solution 6 Holdings' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Solution 6 Holdings' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Solution 6 Holdings' accountClass='Sub Account' securityId='68385711' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Open Telecomm.' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Open Telecomm.' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Open Telecomm.' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Open Telecomm.' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Open Telecomm.' accountClass='Sub Account' securityId='68385712' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Brambles Industries' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Brambles Industries' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Brambles Industries' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Brambles Industries' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Brambles Industries' accountClass='Sub Account' securityId='68385713' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Hardie (James) Inds.' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Hardie (James) Inds.' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Hardie (James) Inds.' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Hardie (James) Inds.' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Hardie (James) Inds.' accountClass='Sub Account' securityId='68385714' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Australian Magnesium' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Australian Magnesium' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Australian Magnesium' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Australian Magnesium' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Australian Magnesium' accountClass='Sub Account' securityId='827381' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Dioro Exploration Nl' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Dioro Exploration Nl' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Dioro Exploration Nl' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Dioro Exploration Nl' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Dioro Exploration Nl' accountClass='Sub Account' securityId='848291' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Harts Australasia' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Harts Australasia' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Harts Australasia' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Harts Australasia' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Harts Australasia' accountClass='Sub Account' securityId='68385715' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Suncorp-Metway' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Suncorp-Metway' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Suncorp-Metway' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Suncorp-Metway' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Suncorp-Metway' accountClass='Sub Account' securityId='68385716' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Environmental Solut.' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Environmental Solut.' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Environmental Solut.' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Environmental Solut.' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Environmental Solut.' accountClass='Sub Account' securityId='728902' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Csr Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Csr Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Csr Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Csr Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Csr Limited' accountClass='Sub Account' securityId='723139' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='St Barbara Mines' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='St Barbara Mines' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='St Barbara Mines' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='St Barbara Mines' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='St Barbara Mines' accountClass='Sub Account' securityId='728701' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Pos.It.Ive Techno.' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Pos.It.Ive Techno.' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Pos.It.Ive Techno.' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Pos.It.Ive Techno.' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Pos.It.Ive Techno.' accountClass='Sub Account' securityId='68385717' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Ellendale Resources' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Ellendale Resources' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Ellendale Resources' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Ellendale Resources' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Ellendale Resources' accountClass='Sub Account' securityId='68385718' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Alintagas Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Alintagas Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Alintagas Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Alintagas Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Alintagas Limited' accountClass='Sub Account' securityId='68385719' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='St George Bank' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='St George Bank' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='St George Bank' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='St George Bank' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='St George Bank' accountClass='Sub Account' securityId='68385720' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='David Jones Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='David Jones Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='David Jones Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='David Jones Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='David Jones Limited' accountClass='Sub Account' securityId='723004' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='77600' name='Wesfarmers Limited' accountClass='Sub Account' securityId='711425' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='23900' name='Wesfarmers Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='37500' name='Wesfarmers Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='62000' name='Wesfarmers Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='83000' name='Wesfarmers Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='62000' name='Stockford Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Stockford Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Stockford Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Stockford Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Stockford Limited' accountClass='Sub Account' securityId='68385721' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Computershare Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Computershare Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Computershare Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Computershare Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Computershare Ltd' accountClass='Sub Account' securityId='720703' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Powerlan Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Powerlan Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Powerlan Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Powerlan Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Powerlan Limited' accountClass='Sub Account' securityId='823111' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Erg Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Erg Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Erg Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Erg Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Erg Limited' accountClass='Sub Account' securityId='68385722' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='77600' name='Woolworths Limited' accountClass='Sub Account' securityId='697387' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='83000' name='Woolworths Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='62000' name='Woolworths Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Woolworths Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Woolworths Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='62000' name='Resmed Inc' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Resmed Inc' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Resmed Inc' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Resmed Inc' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Resmed Inc' accountClass='Sub Account' securityId='724760' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Kaz Group Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Kaz Group Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Kaz Group Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Kaz Group Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Kaz Group Ltd' accountClass='Sub Account' securityId='68385723' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='77600' name='Newcrest Mining Limited' accountClass='Sub Account' securityId='699596' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='37500' name='Newcrest Mining Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='83000' name='Newcrest Mining Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='62000' name='Newcrest Mining Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='23900' name='Newcrest Mining Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='62000' name='Aurion Gold Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Aurion Gold Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Aurion Gold Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Aurion Gold Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Aurion Gold Limited' accountClass='Sub Account' securityId='68385724' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='OZ Minerals Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='OZ Minerals Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='OZ Minerals Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='OZ Minerals Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='OZ Minerals Ltd' accountClass='Sub Account' securityId='730052' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Sons of Gwalia Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Sons of Gwalia Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Sons of Gwalia Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Sons of Gwalia Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Sons of Gwalia Limited' accountClass='Sub Account' securityId='68385725' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Bolnisi Gold Nl' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Bolnisi Gold Nl' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Bolnisi Gold Nl' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Bolnisi Gold Nl' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Bolnisi Gold Nl' accountClass='Sub Account' securityId='68385726' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Westmag Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Westmag Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Westmag Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Westmag Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Westmag Limited' accountClass='Sub Account' securityId='68385727' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Sigma Pharmaceuticals Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Sigma Pharmaceuticals Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Sigma Pharmaceuticals Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Sigma Pharmaceuticals Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Sigma Pharmaceuticals Limited' accountClass='Sub Account' securityId='700624' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='77600' name='Rio Tinto Limited' accountClass='Sub Account' securityId='691026' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Rio Tinto Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='23900' name='Rio Tinto Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='37500' name='Rio Tinto Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='83000' name='Rio Tinto Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='62000' name='Smorgon Steel Group Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Smorgon Steel Group Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Smorgon Steel Group Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Smorgon Steel Group Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Smorgon Steel Group Limited' accountClass='Sub Account' securityId='68385728' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='77600' name='Awb Limited' accountClass='Sub Account' securityId='841868' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Awb Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='83000' name='Awb Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='23900' name='Awb Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='37500' name='Awb Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='62000' name='Mincor Resources Nl' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Mincor Resources Nl' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Mincor Resources Nl' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Mincor Resources Nl' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Mincor Resources Nl' accountClass='Sub Account' securityId='689188' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Cockatoo Ridge Wines Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Cockatoo Ridge Wines Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Cockatoo Ridge Wines Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Cockatoo Ridge Wines Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Cockatoo Ridge Wines Limited' accountClass='Sub Account' securityId='835181' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Ezenet Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Ezenet Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Ezenet Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Ezenet Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Ezenet Limited' accountClass='Sub Account' securityId='825882' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='77600' name='Bhp Billiton Limited' accountClass='Sub Account' securityId='691680' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Bhp Billiton Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='23900' name='Bhp Billiton Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='37500' name='Bhp Billiton Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='83000' name='Bhp Billiton Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Nufarm Limited' accountClass='Sub Account' securityId='707617' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Nufarm Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='23900' name='Nufarm Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='37500' name='Nufarm Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='83000' name='Nufarm Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='62000' name='View Resources Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='View Resources Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='View Resources Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='View Resources Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='View Resources Limited' accountClass='Sub Account' securityId='798637' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Tantalum Australia Nl' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Tantalum Australia Nl' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Tantalum Australia Nl' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Tantalum Australia Nl' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Tantalum Australia Nl' accountClass='Sub Account' securityId='68385729' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Aft Corporation Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Aft Corporation Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Aft Corporation Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Aft Corporation Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Aft Corporation Limited' accountClass='Sub Account' securityId='680476' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Henry Walker Eltin Group Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Henry Walker Eltin Group Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Henry Walker Eltin Group Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Henry Walker Eltin Group Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Henry Walker Eltin Group Limited' accountClass='Sub Account' securityId='694357' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Australian Mines Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Australian Mines Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Australian Mines Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Australian Mines Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Australian Mines Limited' accountClass='Sub Account' securityId='692796' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Arc Energy Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Arc Energy Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Arc Energy Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Arc Energy Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Arc Energy Limited' accountClass='Sub Account' securityId='68385730' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Voyager Energy Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Voyager Energy Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Voyager Energy Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Voyager Energy Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Voyager Energy Limited' accountClass='Sub Account' securityId='68385731' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Aim Resources Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Aim Resources Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Aim Resources Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Aim Resources Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Aim Resources Limited' accountClass='Sub Account' securityId='68385732' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Halcyon Group Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Halcyon Group Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Halcyon Group Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Halcyon Group Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Halcyon Group Limited' accountClass='Sub Account' securityId='68385733' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Tectonic Resources Nl' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Tectonic Resources Nl' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Tectonic Resources Nl' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Tectonic Resources Nl' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Tectonic Resources Nl' accountClass='Sub Account' securityId='831574' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='77600' name='Caltex Australia Limited' accountClass='Sub Account' securityId='733669' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='37500' name='Caltex Australia Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='83000' name='Caltex Australia Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='62000' name='Caltex Australia Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='23900' name='Caltex Australia Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='62000' name='DCA Group Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='DCA Group Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='DCA Group Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='DCA Group Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='DCA Group Limited' accountClass='Sub Account' securityId='68385734' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Voyager Option Expiring 31/03/2006' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Voyager Option Expiring 31/03/2006' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Voyager Option Expiring 31/03/2006' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Voyager Option Expiring 31/03/2006' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Voyager Option Expiring 31/03/2006' accountClass='Sub Account' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Tethyan Copper Company Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Tethyan Copper Company Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Tethyan Copper Company Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Tethyan Copper Company Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Tethyan Copper Company Limited' accountClass='Sub Account' securityId='68385735' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Iinet Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Iinet Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Iinet Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Iinet Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Iinet Limited' accountClass='Sub Account' securityId='704018' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Lion Selection Group Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Lion Selection Group Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Lion Selection Group Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Lion Selection Group Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Lion Selection Group Limited' accountClass='Sub Account' securityId='68385736' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Colltech Aust Ltd Option Expiring 30/06/2005' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Colltech Aust Ltd Option Expiring 30/06/2005' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Colltech Aust Ltd Option Expiring 30/06/2005' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Colltech Aust Ltd Option Expiring 30/06/2005' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Colltech Aust Ltd Option Expiring 30/06/2005' accountClass='Sub Account' securityId='68385737' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='77600' name='James Hardie Industries Nv' accountClass='Sub Account' securityId='728041' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='23900' name='James Hardie Industries Nv' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='37500' name='James Hardie Industries Nv' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='83000' name='James Hardie Industries Nv' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='62000' name='James Hardie Industries Nv' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='62000' name='Home Building Society Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Home Building Society Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Home Building Society Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Home Building Society Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Home Building Society Limited' accountClass='Sub Account' securityId='68385738' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='77600' name='Bendigo and Adelaide Bank Limited' accountClass='Sub Account' securityId='714229' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='23900' name='Bendigo and Adelaide Bank Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Bendigo and Adelaide Bank Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='37500' name='Bendigo and Adelaide Bank Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='62000' name='Bendigo and Adelaide Bank Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='62000' name='Zinifex Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Zinifex Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Zinifex Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Zinifex Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Zinifex Limited' accountClass='Sub Account' securityId='68385739' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Tap Oil Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Tap Oil Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Tap Oil Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Tap Oil Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Tap Oil Limited' accountClass='Sub Account' securityId='692575' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Babcock and Brown Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Babcock and Brown Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Babcock and Brown Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Babcock and Brown Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Babcock and Brown Limited' accountClass='Sub Account' securityId='68385663' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Crane Group Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Crane Group Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Crane Group Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Crane Group Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Crane Group Limited' accountClass='Sub Account' securityId='837502' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Wasabi Energy Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Wasabi Energy Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Wasabi Energy Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Wasabi Energy Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Wasabi Energy Limited' accountClass='Sub Account' securityId='688847' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Henderson Group PLC' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Henderson Group PLC' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Henderson Group PLC' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Henderson Group PLC' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Henderson Group PLC' accountClass='Sub Account' securityId='68385666' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Foster&apos;s Group Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Foster&apos;s Group Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Foster&apos;s Group Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Foster&apos;s Group Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Foster&apos;s Group Limited' accountClass='Sub Account' securityId='825626' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Babcock and Brown Infrastructure Group (INACTIVE)' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Babcock and Brown Infrastructure Group (INACTIVE)' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Babcock and Brown Infrastructure Group (INACTIVE)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Babcock and Brown Infrastructure Group (INACTIVE)' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Babcock and Brown Infrastructure Group (INACTIVE)' accountClass='Sub Account' securityId='68385751' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Perilya Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Perilya Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Perilya Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Perilya Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Perilya Limited' accountClass='Sub Account' securityId='683400' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='77600' name='Fairfax Media Limited' accountClass='Sub Account' securityId='680760' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='83000' name='Fairfax Media Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='62000' name='Fairfax Media Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='23900' name='Fairfax Media Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='37500' name='Fairfax Media Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='62000' name='Allco Finance Grooup Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Allco Finance Grooup Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Allco Finance Grooup Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Allco Finance Grooup Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Allco Finance Grooup Limited' accountClass='Sub Account' securityId='68385740' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Medec Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Medec Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Medec Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Medec Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Medec Limited' accountClass='Sub Account' securityId='68385741' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Becton Property Group Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Becton Property Group Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Becton Property Group Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Becton Property Group Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Becton Property Group Limited' accountClass='Sub Account' securityId='728954' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Troy Resources Nl' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Troy Resources Nl' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Troy Resources Nl' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Troy Resources Nl' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Troy Resources Nl' accountClass='Sub Account' securityId='683281' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Senetas Corporation Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Senetas Corporation Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Senetas Corporation Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Senetas Corporation Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Senetas Corporation Limited' accountClass='Sub Account' securityId='710306' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Petsec Energy Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Petsec Energy Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Petsec Energy Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Petsec Energy Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Petsec Energy Limited' accountClass='Sub Account' securityId='692769' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Tanami Gold Nl' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Tanami Gold Nl' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Tanami Gold Nl' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Tanami Gold Nl' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Tanami Gold Nl' accountClass='Sub Account' securityId='721279' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Hardman Resources Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Hardman Resources Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Hardman Resources Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Hardman Resources Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Hardman Resources Limited' accountClass='Sub Account' securityId='68385742' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Avoca Resources Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Avoca Resources Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Avoca Resources Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Avoca Resources Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Avoca Resources Limited' accountClass='Sub Account' securityId='839866' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Austindo Resources Corporation Nl' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Austindo Resources Corporation Nl' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Austindo Resources Corporation Nl' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Austindo Resources Corporation Nl' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Austindo Resources Corporation Nl' accountClass='Sub Account' securityId='681639' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Toro Energy Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Toro Energy Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Toro Energy Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Toro Energy Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Toro Energy Limited' accountClass='Sub Account' securityId='719052' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Magellan Financial Group Limited-INACTIVE' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Magellan Financial Group Limited-INACTIVE' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Magellan Financial Group Limited-INACTIVE' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Magellan Financial Group Limited-INACTIVE' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Magellan Financial Group Limited-INACTIVE' accountClass='Sub Account' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Allco Finance Group Limited - INACTIVE' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Allco Finance Group Limited - INACTIVE' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Allco Finance Group Limited - INACTIVE' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Allco Finance Group Limited - INACTIVE' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Allco Finance Group Limited - INACTIVE' accountClass='Sub Account' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Argo Investments Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Argo Investments Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Argo Investments Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Argo Investments Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Argo Investments Limited' accountClass='Sub Account' securityId='710372' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='77600' name='Macquarie Group Limited' accountClass='Sub Account' securityId='712704' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='83000' name='Macquarie Group Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='37500' name='Macquarie Group Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Macquarie Group Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='62000' name='Macquarie Group Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='62000' name='Ansell Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Ansell Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Ansell Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Ansell Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Ansell Limited' accountClass='Sub Account' securityId='679215' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='77600' name='Alumina Limited' accountClass='Sub Account' securityId='721578' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Alumina Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Alumina Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='83000' name='Alumina Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='23900' name='Alumina Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='62000' name='Pengana Managers Limited-INACTIVE' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Pengana Managers Limited-INACTIVE' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Pengana Managers Limited-INACTIVE' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Pengana Managers Limited-INACTIVE' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Pengana Managers Limited-INACTIVE' accountClass='Sub Account' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Great Southern Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Great Southern Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Great Southern Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Great Southern Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Great Southern Limited' accountClass='Sub Account' securityId='844407' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='77600' name='Brambles Limited' accountClass='Sub Account' securityId='727423' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='37500' name='Brambles Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Brambles Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Brambles Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='62000' name='Brambles Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='62000' name='Customers Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Customers Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Customers Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Customers Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Customers Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='808640' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Australian Worldwide Exploration Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Australian Worldwide Exploration Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Australian Worldwide Exploration Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Australian Worldwide Exploration Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Australian Worldwide Exploration Limited' accountClass='Sub Account' securityId='697511' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='News Corporation' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='News Corporation' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='News Corporation' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='News Corporation' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='News Corporation' accountClass='Sub Account' securityId='740634' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Cbh Resources Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Cbh Resources Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Cbh Resources Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Cbh Resources Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Cbh Resources Limited' accountClass='Sub Account' securityId='843440' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Fkp Property Group - Ordinary/Units Fully Paid Stapled Securities' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Fkp Property Group - Ordinary/Units Fully Paid Stapled Securities' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Fkp Property Group - Ordinary/Units Fully Paid Stapled Securities' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Fkp Property Group - Ordinary/Units Fully Paid Stapled Securities' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Fkp Property Group - Ordinary/Units Fully Paid Stapled Securities' accountClass='Sub Account' securityId='680474' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='77600' name='Symbion Health Limited' accountClass='Sub Account' securityId='68385743' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='23900' name='Symbion Health Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='37500' name='Symbion Health Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='83000' name='Symbion Health Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='62000' name='Symbion Health Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='62000' name='Murchison Metals Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Murchison Metals Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Murchison Metals Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Murchison Metals Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Murchison Metals Ltd' accountClass='Sub Account' securityId='712100' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Abb Grain Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Abb Grain Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Abb Grain Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Abb Grain Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Abb Grain Limited' accountClass='Sub Account' securityId='68385744' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Auselect Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Auselect Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Auselect Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Auselect Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Auselect Limited' accountClass='Sub Account' securityId='68385745' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Magellan Flagship Fund Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Magellan Flagship Fund Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Magellan Flagship Fund Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Magellan Flagship Fund Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Magellan Flagship Fund Limited' accountClass='Sub Account' securityId='683428' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Magellan Financial Group Ltd-options expiring 30 June 2009' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Magellan Financial Group Ltd-options expiring 30 June 2009' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Magellan Financial Group Ltd-options expiring 30 June 2009' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Magellan Financial Group Ltd-options expiring 30 June 2009' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Magellan Financial Group Ltd-options expiring 30 June 2009' accountClass='Sub Account' securityId='68385746' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Telstra Corporation Limited - Instalment' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Telstra Corporation Limited - Instalment' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Telstra Corporation Limited - Instalment' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Telstra Corporation Limited - Instalment' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Telstra Corporation Limited - Instalment' accountClass='Sub Account' securityId='68385754' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='77600' name='Commonwealth Bank of Australia' accountClass='Sub Account' securityId='717279' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='37500' name='Commonwealth Bank of Australia' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='83000' name='Commonwealth Bank of Australia' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='23900' name='Commonwealth Bank of Australia' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='62000' name='Commonwealth Bank of Australia' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='77600' name='Leighton Holdings Limited' accountClass='Sub Account' securityId='694710' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='23900' name='Leighton Holdings Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='37500' name='Leighton Holdings Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='83000' name='Leighton Holdings Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='62000' name='Leighton Holdings Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='62000' name='Boom Logistics Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Boom Logistics Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Boom Logistics Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Boom Logistics Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Boom Logistics Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='693028' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Magna Mining Nl - Option Expiring 30-Nov-2009' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Magna Mining Nl - Option Expiring 30-Nov-2009' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Magna Mining Nl - Option Expiring 30-Nov-2009' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Magna Mining Nl - Option Expiring 30-Nov-2009' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Magna Mining Nl - Option Expiring 30-Nov-2009' accountClass='Sub Account' securityId='68385747' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Magna Mining Nl - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Magna Mining Nl - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Magna Mining Nl - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Magna Mining Nl - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Magna Mining Nl - Ordinary Fully Paid' accountClass='Sub Account' securityId='685853' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Metals Australia Ltd - Option Expiring 31- Dec 2010' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Metals Australia Ltd - Option Expiring 31- Dec 2010' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Metals Australia Ltd - Option Expiring 31- Dec 2010' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Metals Australia Ltd - Option Expiring 31- Dec 2010' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Metals Australia Ltd - Option Expiring 31- Dec 2010' accountClass='Sub Account' securityId='68385748' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Intrepid Mines Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Intrepid Mines Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Intrepid Mines Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Intrepid Mines Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Intrepid Mines Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='727687' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='77600' name='Origin Energy Limited' accountClass='Sub Account' securityId='696930' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='83000' name='Origin Energy Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='37500' name='Origin Energy Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='62000' name='Origin Energy Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='23900' name='Origin Energy Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='62000' name='Viralytics Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Viralytics Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Viralytics Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Viralytics Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Viralytics Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='706052' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Tox Free Solutions Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Tox Free Solutions Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Tox Free Solutions Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Tox Free Solutions Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Tox Free Solutions Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='695192' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='77600' name='UGL Limited' accountClass='Sub Account' securityId='712376' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='UGL Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='83000' name='UGL Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='23900' name='UGL Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='37500' name='UGL Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='62000' name='Quickstep Holdings Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Quickstep Holdings Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Quickstep Holdings Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Quickstep Holdings Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Quickstep Holdings Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='722922' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Queensland Mining Corporation Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Queensland Mining Corporation Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Queensland Mining Corporation Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Queensland Mining Corporation Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Queensland Mining Corporation Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='708265' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Medusa Mining Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Medusa Mining Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Medusa Mining Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Medusa Mining Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Medusa Mining Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='685286' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='77600' name='Sonic Healthcare Limited' accountClass='Sub Account' securityId='711309' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='23900' name='Sonic Healthcare Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='62000' name='Sonic Healthcare Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='83000' name='Sonic Healthcare Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='37500' name='Sonic Healthcare Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='62000' name='Gage Roads Brewing Co Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Gage Roads Brewing Co Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Gage Roads Brewing Co Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Gage Roads Brewing Co Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Gage Roads Brewing Co Limited' accountClass='Sub Account' securityId='699826' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Kingsrose Mining Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Kingsrose Mining Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Kingsrose Mining Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Kingsrose Mining Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Kingsrose Mining Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='707330' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Lynas Corporation Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Lynas Corporation Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Lynas Corporation Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Lynas Corporation Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Lynas Corporation Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='716705' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Aquila Resources Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Aquila Resources Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Aquila Resources Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Aquila Resources Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Aquila Resources Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='703720' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='West African Resources Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='West African Resources Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='West African Resources Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='West African Resources Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='West African Resources Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='731946' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='77600' name='Boral Limited' accountClass='Sub Account' securityId='691139' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='23900' name='Boral Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='62000' name='Boral Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='83000' name='Boral Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='37500' name='Boral Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='62000' name='Platinum Australia Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Platinum Australia Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Platinum Australia Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Platinum Australia Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Platinum Australia Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='680573' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Falcon Minerals Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Falcon Minerals Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Falcon Minerals Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Falcon Minerals Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Falcon Minerals Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='698540' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Regis Resources Limited - Option Expiring 31-Jan-2014' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Regis Resources Limited - Option Expiring 31-Jan-2014' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Regis Resources Limited - Option Expiring 31-Jan-2014' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Regis Resources Limited - Option Expiring 31-Jan-2014' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Regis Resources Limited - Option Expiring 31-Jan-2014' accountClass='Sub Account' securityId='718564' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='77600' name='Worleyparsons Limited' accountClass='Sub Account' securityId='718914' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='37500' name='Worleyparsons Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='83000' name='Worleyparsons Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='23900' name='Worleyparsons Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='62000' name='Worleyparsons Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='62000' name='Iron Ore Holdings Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Iron Ore Holdings Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Iron Ore Holdings Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Iron Ore Holdings Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Iron Ore Holdings Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='681614' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Uranex Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Uranex Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Uranex Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Uranex Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Uranex Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='707926' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Goconnect Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Goconnect Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Goconnect Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Goconnect Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Goconnect Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='731013' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='77600' name='Fortescue Metals Group Ltd' accountClass='Sub Account' securityId='683188' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='23900' name='Fortescue Metals Group Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Fortescue Metals Group Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='37500' name='Fortescue Metals Group Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='62000' name='Fortescue Metals Group Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='62000' name='Otto Energy Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Otto Energy Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Otto Energy Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Otto Energy Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Otto Energy Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='700455' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Regis Resources Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Regis Resources Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Regis Resources Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Regis Resources Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Regis Resources Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='727776' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Norwest Energy Nl - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Norwest Energy Nl - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Norwest Energy Nl - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Norwest Energy Nl - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Norwest Energy Nl - Ordinary Fully Paid' accountClass='Sub Account' securityId='690580' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Ucl Resources Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Ucl Resources Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Ucl Resources Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Ucl Resources Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Ucl Resources Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='702164' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Greencross Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Greencross Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Greencross Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Greencross Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Greencross Limited - Ordinary Fully Paid' accountClass='Sub Account' securityId='693355' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='Westpac Banking Corporation - Convertible Preference Shares' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Westpac Banking Corporation - Convertible Preference Shares' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23900' name='Westpac Banking Corporation - Convertible Preference Shares' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='Westpac Banking Corporation - Convertible Preference Shares' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='77600' name='Westpac Banking Corporation - Convertible Preference Shares' accountClass='Sub Account' securityId='681056' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='62000' name='HHG PLC' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='HHG PLC' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='83000' name='HHG PLC' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='23900' name='HHG PLC' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='77700' name='HHG PLC' accountClass='Sub Account' securityId='68385756' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='61800' name='Amp Office Trust' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Amp Office Trust' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='83000' name='Amp Office Trust' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='23800' name='Amp Office Trust' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='78200' name='Amp Office Trust' accountClass='Sub Account' securityId='68385749' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='61800' name='Babcock and Brown Japan Property Trust' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Babcock and Brown Japan Property Trust' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='83000' name='Babcock and Brown Japan Property Trust' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='23800' name='Babcock and Brown Japan Property Trust' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='78200' name='Babcock and Brown Japan Property Trust' accountClass='Sub Account' securityId='68385750' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='61800' name='FKP Property Group' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='FKP Property Group' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='83000' name='FKP Property Group' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='23800' name='FKP Property Group' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='78200' name='FKP Property Group' accountClass='Sub Account' securityId='680474' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='78200' name='Babcock &amp; Brown Infrastructure Group - Stapled Securities Fully Paid' accountClass='Sub Account' securityId='68385751' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='37500' name='Babcock &amp; Brown Infrastructure Group - Stapled Securities Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='83000' name='Babcock &amp; Brown Infrastructure Group - Stapled Securities Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='61800' name='Babcock &amp; Brown Infrastructure Group - Stapled Securities Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='23800' name='Babcock &amp; Brown Infrastructure Group - Stapled Securities Fully Paid' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='61800' name='Magellan Financial Group Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='Magellan Financial Group Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='83000' name='Magellan Financial Group Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='23800' name='Magellan Financial Group Limited' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='78200' name='Magellan Financial Group Limited' accountClass='Sub Account' securityId='697312' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='78200' name='Transurban Group - Ordinary Shares/Units Fully Paid Triple Stapled' accountClass='Sub Account' securityId='711882' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='23800' name='Transurban Group - Ordinary Shares/Units Fully Paid Triple Stapled' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='61800' name='Transurban Group - Ordinary Shares/Units Fully Paid Triple Stapled' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='83000' name='Transurban Group - Ordinary Shares/Units Fully Paid Triple Stapled' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='37500' name='Transurban Group - Ordinary Shares/Units Fully Paid Triple Stapled' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='83000' name='AMP Office Trust' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='37500' name='AMP Office Trust' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23800' name='AMP Office Trust' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='61800' name='AMP Office Trust' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='78400' name='AMP Office Trust' accountClass='Sub Account' securityId='68385755' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='83000' name='Sea Pines Investment Trust' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='37500' name='Sea Pines Investment Trust' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='23800' name='Sea Pines Investment Trust' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='61800' name='Sea Pines Investment Trust' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='78400' name='Sea Pines Investment Trust' accountClass='Sub Account' securityId='68385752' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='25000' name='Sea Pines Investment Trust' accountClass='Sub Account' securityId='68385752' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='27850' name='Water Tank (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='28000' name='Water Tank (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='25500' name='Water Tank (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='27800' name='Water Tank (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='37500' name='Water Tank (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='33400' name='Water Tank (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='83000' name='Water Tank (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='76550' name='Water Tank (Carter Road)' accountClass='Sub Account' securityId='68385678' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='27850' name='Tenant&apos;s Tank (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='28000' name='Tenant&apos;s Tank (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='25500' name='Tenant&apos;s Tank (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='27800' name='Tenant&apos;s Tank (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='37500' name='Tenant&apos;s Tank (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='33400' name='Tenant&apos;s Tank (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='83000' name='Tenant&apos;s Tank (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='76550' name='Tenant&apos;s Tank (Carter Road)' accountClass='Sub Account' securityId='68385679' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='27850' name='Shed (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='28000' name='Shed (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='25500' name='Shed (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='27800' name='Shed (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='37500' name='Shed (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='33400' name='Shed (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='83000' name='Shed (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='76550' name='Shed (Carter Road)' accountClass='Sub Account' securityId='68385680' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='33500' name='Cattle Yards Fencing (Carter Road)' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='25000' name='Challenge Cash Management Account' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='25000' name='Challenge Bank Term Deposit' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='25000' name='Villa 25 Westview Parade Port Bouvard' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='25500' name='Luxury car lease' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='25600' name='BMW 1998 1AHI208' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='26500' name='Other Income' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='26600' name='Demerger Dividend- Mincor' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='33400' name='Luxury car lease' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='34000' name='Filing Fees' accountClass='Normal' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='35100' name='General - Non deductible' accountClass='Normal' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='37500' name='Villa 25 Westview Parade Port Bouvard' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='37500' name='General Investment Expenses' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='37500' name='Septic/Water Tank' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='60100' name='Luxury Car Lease Loan' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='60100' name='Luxury Car Lease Finance Charge Component' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='62000' name='ANZ DRP Residual' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='62501' name='DRP Residual Value - Westfarmer Ltd' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='37500' name='MQG DRP Residual' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='25000' name='MQG DRP Residual' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='MQG DRP Residual' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='26500' name='MQG DRP Residual' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='76000' name='MQG DRP Residual' accountClass='Sub Account' securityId='68385674' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='37500' name='WPL DRP Residual' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='25000' name='WPL DRP Residual' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='83000' name='WPL DRP Residual' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='26500' name='WPL DRP Residual' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='76000' name='WPL DRP Residual' accountClass='Sub Account' securityId='68385675' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='25500' name='Luxury car lease' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='33400' name='Luxury car lease' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='37500' name='Luxury car lease' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='83000' name='Luxury car lease' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='73850' name='Luxury car lease' accountClass='Sub Account' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='83000' name='Villa 25 Westview Parade Port Bouvard' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='37500' name='Villa 25 Westview Parade Port Bouvard' accountClass='Sub Account' securityId='' chartAccountType='{label=Expense, minCode=30000, maxCode=47999}' />
	< code='81000' name='Villa 25 Westview Parade Port Bouvard' accountClass='Sub Account' securityId='' chartAccountType='{label=Liability, minCode=80000, maxCode=89999}' />
	< code='65000' name='Villa 25 Westview Parade Port Bouvard' accountClass='Sub Account' securityId='' chartAccountType='{label=Asset, minCode=60000, maxCode=69999}' />
	< code='25000' name='Villa 25 Westview Parade Port Bouvard' accountClass='Sub Account' securityId='' chartAccountType='{label=Income, minCode=20000, maxCode=29999}' />
	< code='74250' name='Villa 25 Westview Parade Port Bouvard' accountClass='Sub Account' securityId='' chartAccountType='{label=Investment, minCode=70000, maxCode=79999}' />
	< code='99700' name='Suspense 1691423' accountClass='Normal' securityId='' chartAccountType='{label=Unallocated, minCode=90000, maxCode=99999}' />
	< code='48100' name='(Division 293 Tax) drnwArn,  h  JhB rJ - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='51900' name='(Division 293 Tax) drnwArn,  h  JhB rJ - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='48100' name='(Division 293 Tax) Aedrwdn, uuaanaurK s - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='51900' name='(Division 293 Tax) Aedrwdn, uuaanaurK s - Pension (ABP 1)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='48100' name='(Division 293 Tax) Aedrwdn, uuaanaurK s - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='51900' name='(Division 293 Tax) Aedrwdn, uuaanaurK s - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='48100' name='(Division 293 Tax) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='51900' name='(Division 293 Tax) dAwwews, lJaraooara olta - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='48100' name='(Division 293 Tax) drnwArn,  h  JhB rJ - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='51900' name='(Division 293 Tax) drnwArn,  h  JhB rJ - Pension (ABP 2)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='48100' name='(Division 293 Tax) Aedrwdn, uuaanaurK s - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='51900' name='(Division 293 Tax) Aedrwdn, uuaanaurK s - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='48100' name='(Division 293 Tax) drnwArn,  h  JhB rJ - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='51900' name='(Division 293 Tax) drnwArn,  h  JhB rJ - Pension (ABP 3)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='48100' name='(Division 293 Tax) Aedrwdn, uuaanaurK s - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='51900' name='(Division 293 Tax) Aedrwdn, uuaanaurK s - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='48100' name='(Division 293 Tax) drnwArn,  h  JhB rJ - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='51900' name='(Division 293 Tax) drnwArn,  h  JhB rJ - Pension (ABP 4)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='48100' name='(Division 293 Tax) Aedrwdn, uuaanaurK s - Pension (ABP 5)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='51900' name='(Division 293 Tax) Aedrwdn, uuaanaurK s - Pension (ABP 5)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='48100' name='(Division 293 Tax) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='51900' name='(Division 293 Tax) drnwArn,  h  JhB rJ - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
	< code='48100' name='(Division 293 Tax) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Income - Member, minCode=0, maxCode=0}' />
	< code='51900' name='(Division 293 Tax) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)' accountClass='Sub Account' securityId='' chartAccountType='{label=Member, minCode=50000, maxCode=59999}' />
</root>

```

