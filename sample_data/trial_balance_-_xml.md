# Trial Balance - XML

#### cURL Request :

```javascript

curl -X POST https://api-staging.bgl360.com.au/fund/trialBalance.xml?fundId=0000000048f240bd0148f28816c80017 --header "Authorization:bearer df2f0e40-606f-4311-8066-590732fd126b"

```

#### Part of the Response Data :

```xml

<root xmlns='http://www.bglcorp.com.au'>
  <TrialBalance>
    <FundId>0000000048f240bd0148f28816c80017</FundId>
    <Start>Tue Jan 01 00:00:00 UTC 2013</Start>
    <End>Fri Jan 01 00:00:00 UTC 2016</End>
    <Data>
        ...
        <Data>
            <AccountClass>S</AccountClass>
            <AccountCode>50010/ANWKSR00005P</AccountCode>
            <AccountType>
                <Label>Member</Label>
                <MinCode>50000</MinCode>
                <MaxCode>59999</MaxCode>
                <Name>Member</Name>
            </AccountType>
            <Name>
                (Opening Balance) Aedrwdn, uuaanaurK s - Pension (ABP 5)
            </Name>
            <Units/>
            <Debits>0</Debits>
            <Credits>438984.47</Credits>
            <UnitsPrev>0</UnitsPrev>
            <DebitsPrev>0</DebitsPrev>
            <CreditsPrev>0</CreditsPrev>
            <BalancePrev>0</BalancePrev>
        </Data>
        <Data>
            <AccountClass>S</AccountClass>
            <AccountCode>50010/ANWKSR00006A</AccountCode>
            <AccountType>
                <Label>Member</Label>
                <MinCode>50000</MinCode>
                <MaxCode>59999</MaxCode>
                <Name>Member</Name>
            </AccountType>
            <Name>
                (Opening Balance) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)
            </Name>
            <Units/>
            <Debits>0</Debits>
            <Credits>2358.46</Credits>
            <UnitsPrev>0</UnitsPrev>
            <DebitsPrev>0</DebitsPrev>
            <CreditsPrev>0</CreditsPrev>
            <BalancePrev>0</BalancePrev>
        </Data>
        <Data>
            <AccountClass>S</AccountClass>
            <AccountCode>50010/DEWHY 00001P</AccountCode>
            <AccountType>
                <Label>Member</Label>
                <MinCode>50000</MinCode>
                <MaxCode>59999</MaxCode>
                <Name>Member</Name>
            </AccountType>
            <Name>
                (Opening Balance) drnwArn, h JhB rJ - Pension (ABP 1)
            </Name>
            <Units/>
            <Debits>0</Debits>
            <Credits>1980307.18</Credits>
            <UnitsPrev>0</UnitsPrev>
            <DebitsPrev>0</DebitsPrev>
            <CreditsPrev>0</CreditsPrev>
            <BalancePrev>0</BalancePrev>
        </Data>
        ...
    </Data>
  </TrialBalance>
</root>

```
