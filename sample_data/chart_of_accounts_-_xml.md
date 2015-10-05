# Chart of Accounts - XML

#### cURL Request :

```javascript

curl -X POST https://api-staging.bgl360.com.au/fund/chartAccounts.xml?fundId=0000000048f240bd0148f28816c80017 --header "Authorization:bearer df2f0e40-606f-4311-8066-590732fd126b"

```

#### Part of the Response Data :


```xml
<root xmlns='http://www.bglcorp.com.au'>
  <ChartAccounts>
    <ChartAccount>
        <Code>59500</Code>
        <Name>Self-Insurance Reserve</Name>
        <SubChartAccountCode/>
        <AccountClass>Control</AccountClass>
        <SecurityId/>
        <SecurityCode/>
        <MarketType/>
        <ChartAccountType>
            <Label>Income - Member</Label>
            <MinCode>0</MinCode>
            <MaxCode>0</MaxCode>
            <Name>IncomeMember</Name>
        </ChartAccountType>
    </ChartAccount>
    <ChartAccount>
        <Code>48500</Code>
        <Name>Income Tax Expense</Name>
        <SubChartAccountCode/>
        <AccountClass>Normal</AccountClass>
        <SecurityId/>
        <SecurityCode/>
        <MarketType/>
        <ChartAccountType>
            <Label>Allocation</Label>
            <MinCode>48000</MinCode>
            <MaxCode>49999</MaxCode>
            <Name>Allocation</Name>
        </ChartAccountType>
    </ChartAccount>
    <ChartAccount>
      <Code>83000</Code>
      <Name>Autron Corporation Ltd</Name>
      <SubChartAccountCode>AAT.AX</SubChartAccountCode>
      <AccountClass>Sub Account</AccountClass>
      <SecurityId />
      <SecurityCode />
      <MarketType />
      <ChartAccountType>
        <Label>Liability</Label>
        <MinCode>80000</MinCode>
        <MaxCode>89999</MaxCode>
        <Name>Liability</Name>
      </ChartAccountType>
    </ChartAccount>

  </ChartAccounts>
</root>


```

