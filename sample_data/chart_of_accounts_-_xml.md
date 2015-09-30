# Chart of Accounts - XML

#### cURL Request :

```javascript

curl -X POST https://api-staging.bgl360.com.au/fund/chartAccounts.xml?fundId=0000000048f240bd0148f28816c80017 --header "Authorization:bearer df2f0e40-606f-4311-8066-590732fd126b"

```

#### Part of the Response Data :


```xml
<root xmlns='http://www.bglcorp.com.au'>
  <ChartAccounts>
    ...
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
    <ChartAccount>
      <Code>77600</Code>
      <Name>Coles Myer Limited</Name>
      <SubChartAccountCode>CML.AX</SubChartAccountCode>
      <AccountClass>Sub Account</AccountClass>
      <SecurityId>68385685</SecurityId>
      <SecurityCode />
      <MarketType />
      <ChartAccountType>
        <Label>Investment</Label>
        <MinCode>70000</MinCode>
        <MaxCode>79999</MaxCode>
        <Name>Investment</Name>
      </ChartAccountType>
    </ChartAccount>
    <ChartAccount>
      <Code>62000</Code>
      <Name>Coles Myer Limited</Name>
      <SubChartAccountCode>CML.AX</SubChartAccountCode>
      <AccountClass>Sub Account</AccountClass>
      <SecurityId />
      <SecurityCode />
      <MarketType />
      <ChartAccountType>
        <Label>Asset</Label>
        <MinCode>60000</MinCode>
        <MaxCode>69999</MaxCode>
        <Name>Asset</Name>
      </ChartAccountType>
    </ChartAccount>
    <ChartAccount>
      <Code>37500</Code>
      <Name>Coles Myer Limited</Name>
      <SubChartAccountCode>CML.AX</SubChartAccountCode>
      <AccountClass>Sub Account</AccountClass>
      <SecurityId />
      <SecurityCode />
      <MarketType />
      <ChartAccountType>
        <Label>Expense</Label>
        <MinCode>30000</MinCode>
        <MaxCode>47999</MaxCode>
        <Name>Expense</Name>
      </ChartAccountType>
    </ChartAccount>
    <ChartAccount>
      <Code>23900</Code>
      <Name>Coles Myer Limited</Name>
      <SubChartAccountCode>CML.AX</SubChartAccountCode>
      <AccountClass>Sub Account</AccountClass>
      <SecurityId />
      <SecurityCode />
      <MarketType />
      <ChartAccountType>
        <Label>Income</Label>
        <MinCode>20000</MinCode>
        <MaxCode>29999</MaxCode>
        <Name>Income</Name>
      </ChartAccountType>
    </ChartAccount>
    ...
  </ChartAccounts>
</root>


```

