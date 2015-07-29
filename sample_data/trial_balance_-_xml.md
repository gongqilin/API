# Trial Balance - XML

#### cURL Request :

```javascript

curl -X POST https://api-staging.bgl360.com.au/fund/trialBalance.xml?fundId=0000000048f240bd0148f28816c80017 --header "Authorization:bearer df2f0e40-606f-4311-8066-590732fd126b"

```

#### Response :

```xml

<root xmlns='http://www.bglcorp.com.au'>
  <TrialBalance>
    <FundId>0000000048f240bd0148f28816c80017</FundId>
    <Start>Tue Jan 01 00:00:00 UTC 2013</Start>
    <End>Fri Jan 01 00:00:00 UTC 2016</End>
    <Data>
      <Data>
        <AccountClass>N</AccountClass>
        <AccountType>
          <Label>Income</Label>
          <MinCode>20000</MinCode>
          <MaxCode>29999</MaxCode>
          <Name>Income</Name>
        </AccountType>
        <Name>Changes in Market Values of Investments</Name>
        <Units />
        <Debits>4636.61</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>C</AccountClass>
        <AccountType>
          <Label>Income</Label>
          <MinCode>20000</MinCode>
          <MaxCode>29999</MaxCode>
          <Name>Income</Name>
        </AccountType>
        <Name>Interest Received</Name>
        <Units>0</Units>
        <Debits>0</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Income</Label>
          <MinCode>20000</MinCode>
          <MaxCode>29999</MaxCode>
          <Name>Income</Name>
        </AccountType>
        <Name>Challenge Cash Management Account</Name>
        <Units />
        <Debits>0</Debits>
        <Credits>233000</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>N</AccountClass>
        <AccountType>
          <Label>Allocation</Label>
          <MinCode>48000</MinCode>
          <MaxCode>49999</MaxCode>
          <Name>Allocation</Name>
        </AccountType>
        <Name>Income Tax Expense</Name>
        <Units />
        <Debits>34950</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>N</AccountClass>
        <AccountType>
          <Label>Allocation</Label>
          <MinCode>48000</MinCode>
          <MaxCode>49999</MaxCode>
          <Name>Allocation</Name>
        </AccountType>
        <Name>Profit/Loss Allocation Account</Name>
        <Units />
        <Debits>193413.39</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>C</AccountClass>
        <AccountType>
          <Label>Member</Label>
          <MinCode>50000</MinCode>
          <MaxCode>59999</MaxCode>
          <Name>Member</Name>
        </AccountType>
        <Name>Opening Balance</Name>
        <Units>0</Units>
        <Debits>0</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Member</Label>
          <MinCode>50000</MinCode>
          <MaxCode>59999</MaxCode>
          <Name>Member</Name>
        </AccountType>
        <Name>(Opening Balance) Aedrwdn, uuaanaurK s - Pension (ABP 1)</Name>
        <Units />
        <Debits>0</Debits>
        <Credits>1454359.64</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Member</Label>
          <MinCode>50000</MinCode>
          <MaxCode>59999</MaxCode>
          <Name>Member</Name>
        </AccountType>
        <Name>(Opening Balance) Aedrwdn, uuaanaurK s - Pension (ABP 2)</Name>
        <Units />
        <Debits>0</Debits>
        <Credits>401057.59</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Member</Label>
          <MinCode>50000</MinCode>
          <MaxCode>59999</MaxCode>
          <Name>Member</Name>
        </AccountType>
        <Name>(Opening Balance) Aedrwdn, uuaanaurK s - Pension (ABP 3)</Name>
        <Units />
        <Debits>0</Debits>
        <Credits>46038.69</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Member</Label>
          <MinCode>50000</MinCode>
          <MaxCode>59999</MaxCode>
          <Name>Member</Name>
        </AccountType>
        <Name>(Opening Balance) Aedrwdn, uuaanaurK s - Pension (ABP 4)</Name>
        <Units />
        <Debits>0</Debits>
        <Credits>29.18</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Member</Label>
          <MinCode>50000</MinCode>
          <MaxCode>59999</MaxCode>
          <Name>Member</Name>
        </AccountType>
        <Name>(Opening Balance) Aedrwdn, uuaanaurK s - Pension (ABP 5)</Name>
        <Units />
        <Debits>0</Debits>
        <Credits>438984.47</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Member</Label>
          <MinCode>50000</MinCode>
          <MaxCode>59999</MaxCode>
          <Name>Member</Name>
        </AccountType>
        <Name>(Opening Balance) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)</Name>
        <Units />
        <Debits>0</Debits>
        <Credits>2358.46</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Member</Label>
          <MinCode>50000</MinCode>
          <MaxCode>59999</MaxCode>
          <Name>Member</Name>
        </AccountType>
        <Name>(Opening Balance) drnwArn,  h  JhB rJ - Pension (ABP 1)</Name>
        <Units />
        <Debits>0</Debits>
        <Credits>1980307.18</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Member</Label>
          <MinCode>50000</MinCode>
          <MaxCode>59999</MaxCode>
          <Name>Member</Name>
        </AccountType>
        <Name>(Opening Balance) drnwArn,  h  JhB rJ - Pension (ABP 2)</Name>
        <Units />
        <Debits>0</Debits>
        <Credits>47605.48</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Member</Label>
          <MinCode>50000</MinCode>
          <MaxCode>59999</MaxCode>
          <Name>Member</Name>
        </AccountType>
        <Name>(Opening Balance) drnwArn,  h  JhB rJ - Pension (ABP 3)</Name>
        <Units />
        <Debits>0</Debits>
        <Credits>28.62</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Member</Label>
          <MinCode>50000</MinCode>
          <MaxCode>59999</MaxCode>
          <Name>Member</Name>
        </AccountType>
        <Name>(Opening Balance) drnwArn,  h  JhB rJ - Pension (ABP 4)</Name>
        <Units />
        <Debits>0</Debits>
        <Credits>444526.25</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Member</Label>
          <MinCode>50000</MinCode>
          <MaxCode>59999</MaxCode>
          <Name>Member</Name>
        </AccountType>
        <Name>(Opening Balance) drnwArn,  h  JhB rJ - Accumulation (Accumulation)</Name>
        <Units />
        <Debits>0</Debits>
        <Credits>2288.92</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>C</AccountClass>
        <AccountType>
          <Label>Member</Label>
          <MinCode>50000</MinCode>
          <MaxCode>59999</MaxCode>
          <Name>Member</Name>
        </AccountType>
        <Name>Share of Profit/(Loss)</Name>
        <Units>0</Units>
        <Debits>0</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Member</Label>
          <MinCode>50000</MinCode>
          <MaxCode>59999</MaxCode>
          <Name>Member</Name>
        </AccountType>
        <Name>(Share of Profit/(Loss)) Aedrwdn, uuaanaurK s - Pension (ABP 1)</Name>
        <Units />
        <Debits>16543.15</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Member</Label>
          <MinCode>50000</MinCode>
          <MaxCode>59999</MaxCode>
          <Name>Member</Name>
        </AccountType>
        <Name>(Share of Profit/(Loss)) Aedrwdn, uuaanaurK s - Pension (ABP 2)</Name>
        <Units />
        <Debits>4559.09</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Member</Label>
          <MinCode>50000</MinCode>
          <MaxCode>59999</MaxCode>
          <Name>Member</Name>
        </AccountType>
        <Name>(Share of Profit/(Loss)) Aedrwdn, uuaanaurK s - Pension (ABP 3)</Name>
        <Units />
        <Debits>526.05</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Member</Label>
          <MinCode>50000</MinCode>
          <MaxCode>59999</MaxCode>
          <Name>Member</Name>
        </AccountType>
        <Name>(Share of Profit/(Loss)) Aedrwdn, uuaanaurK s - Pension (ABP 5)</Name>
        <Units />
        <Debits>4991.99</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Member</Label>
          <MinCode>50000</MinCode>
          <MaxCode>59999</MaxCode>
          <Name>Member</Name>
        </AccountType>
        <Name>(Share of Profit/(Loss)) Aedrwdn, uuaanaurK s - Accumulation (Accumulation)</Name>
        <Units />
        <Debits>27.4</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Member</Label>
          <MinCode>50000</MinCode>
          <MaxCode>59999</MaxCode>
          <Name>Member</Name>
        </AccountType>
        <Name>(Share of Profit/(Loss)) drnwArn,  h  JhB rJ - Pension (ABP 1)</Name>
        <Units />
        <Debits>22521.48</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Member</Label>
          <MinCode>50000</MinCode>
          <MaxCode>59999</MaxCode>
          <Name>Member</Name>
        </AccountType>
        <Name>(Share of Profit/(Loss)) drnwArn,  h  JhB rJ - Pension (ABP 2)</Name>
        <Units />
        <Debits>542.49</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Member</Label>
          <MinCode>50000</MinCode>
          <MaxCode>59999</MaxCode>
          <Name>Member</Name>
        </AccountType>
        <Name>(Share of Profit/(Loss)) drnwArn,  h  JhB rJ - Pension (ABP 4)</Name>
        <Units />
        <Debits>5057.74</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Member</Label>
          <MinCode>50000</MinCode>
          <MaxCode>59999</MaxCode>
          <Name>Member</Name>
        </AccountType>
        <Name>(Share of Profit/(Loss)) drnwArn,  h  JhB rJ - Accumulation (Accumulation)</Name>
        <Units />
        <Debits>27.4</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>C</AccountClass>
        <AccountType>
          <Label>Asset - Bank</Label>
          <MinCode>60400</MinCode>
          <MaxCode>60800</MaxCode>
          <Name>AssetBank</Name>
        </AccountType>
        <Name>Bank Accounts</Name>
        <Units>0</Units>
        <Debits>0</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Asset - Bank</Label>
          <MinCode>60400</MinCode>
          <MaxCode>60800</MaxCode>
          <Name>AssetBank</Name>
        </AccountType>
        <Name>Andrews SF share transactions account</Name>
        <Units />
        <Debits>25597.51</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Asset - Bank</Label>
          <MinCode>60400</MinCode>
          <MaxCode>60800</MaxCode>
          <Name>AssetBank</Name>
        </AccountType>
        <Name>Westpac Business Cash Reserve 16-0105</Name>
        <Units />
        <Debits>158367.97</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Asset - Bank</Label>
          <MinCode>60400</MinCode>
          <MaxCode>60800</MaxCode>
          <Name>AssetBank</Name>
        </AccountType>
        <Name>Westpac Business Flexi 27-0988</Name>
        <Units />
        <Debits>50484.69</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Asset - Bank</Label>
          <MinCode>60400</MinCode>
          <MaxCode>60800</MaxCode>
          <Name>AssetBank</Name>
        </AccountType>
        <Name>NAB Term Deposit 11-566-4704</Name>
        <Units />
        <Debits>352041.24</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Asset - Bank</Label>
          <MinCode>60400</MinCode>
          <MaxCode>60800</MaxCode>
          <Name>AssetBank</Name>
        </AccountType>
        <Name>NAB Term Deposit 11-647-3782</Name>
        <Units />
        <Debits>257687.68</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Asset - Bank</Label>
          <MinCode>60400</MinCode>
          <MaxCode>60800</MaxCode>
          <Name>AssetBank</Name>
        </AccountType>
        <Name>NAB Term Deposit 12-914-8292</Name>
        <Units />
        <Debits>225000</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Asset - Bank</Label>
          <MinCode>60400</MinCode>
          <MaxCode>60800</MaxCode>
          <Name>AssetBank</Name>
        </AccountType>
        <Name>Westpac Term Deposit 164325 (Matures 25/03/15)</Name>
        <Units />
        <Debits>150000</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Asset - Bank</Label>
          <MinCode>60400</MinCode>
          <MaxCode>60800</MaxCode>
          <Name>AssetBank</Name>
        </AccountType>
        <Name>Westpac Term Deposit 170346</Name>
        <Units />
        <Debits>350000</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>N</AccountClass>
        <AccountType>
          <Label>Asset</Label>
          <MinCode>60000</MinCode>
          <MaxCode>69999</MaxCode>
          <Name>Asset</Name>
        </AccountType>
        <Name>Sundry Debtors</Name>
        <Units />
        <Debits>1528</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>C</AccountClass>
        <AccountType>
          <Label>Investment</Label>
          <MinCode>70000</MinCode>
          <MaxCode>79999</MaxCode>
          <Name>Investment</Name>
        </AccountType>
        <Name>Fixed Interest Securities (Australian) - Unitised</Name>
        <Units>0</Units>
        <Debits>0</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Investment</Label>
          <MinCode>70000</MinCode>
          <MaxCode>79999</MaxCode>
          <Name>Investment</Name>
        </AccountType>
        <Name>Athena Finance Pty Ltd</Name>
        <Units>1</Units>
        <Debits>100000</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>C</AccountClass>
        <AccountType>
          <Label>Investment</Label>
          <MinCode>70000</MinCode>
          <MaxCode>79999</MaxCode>
          <Name>Investment</Name>
        </AccountType>
        <Name>Other Assets</Name>
        <Units>0</Units>
        <Debits>0</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Investment</Label>
          <MinCode>70000</MinCode>
          <MaxCode>79999</MaxCode>
          <Name>Investment</Name>
        </AccountType>
        <Name>WPL DRP Residual</Name>
        <Units />
        <Debits>25.47</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>C</AccountClass>
        <AccountType>
          <Label>Investment</Label>
          <MinCode>70000</MinCode>
          <MaxCode>79999</MaxCode>
          <Name>Investment</Name>
        </AccountType>
        <Name>Plant and Equipment (at written down value) - Unitised</Name>
        <Units>0</Units>
        <Debits>0</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Investment</Label>
          <MinCode>70000</MinCode>
          <MaxCode>79999</MaxCode>
          <Name>Investment</Name>
        </AccountType>
        <Name>Bore Pump (Carter Road)</Name>
        <Units>1</Units>
        <Debits>2384.34</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Investment</Label>
          <MinCode>70000</MinCode>
          <MaxCode>79999</MaxCode>
          <Name>Investment</Name>
        </AccountType>
        <Name>Pioneer Water Tank (Carter Road)</Name>
        <Units>1</Units>
        <Debits>9467.09</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Investment</Label>
          <MinCode>70000</MinCode>
          <MaxCode>79999</MaxCode>
          <Name>Investment</Name>
        </AccountType>
        <Name>Rainwater Tank (Carter Road)</Name>
        <Units>1</Units>
        <Debits>2323.26</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Investment</Label>
          <MinCode>70000</MinCode>
          <MaxCode>79999</MaxCode>
          <Name>Investment</Name>
        </AccountType>
        <Name>Shed (Carter Road)</Name>
        <Units>1</Units>
        <Debits>125218</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Investment</Label>
          <MinCode>70000</MinCode>
          <MaxCode>79999</MaxCode>
          <Name>Investment</Name>
        </AccountType>
        <Name>Tenant's Tank (Carter Road)</Name>
        <Units>1</Units>
        <Debits>5426.06</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Investment</Label>
          <MinCode>70000</MinCode>
          <MaxCode>79999</MaxCode>
          <Name>Investment</Name>
        </AccountType>
        <Name>Water Tank (Carter Road)</Name>
        <Units>1</Units>
        <Debits>7166.7</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>C</AccountClass>
        <AccountType>
          <Label>Investment</Label>
          <MinCode>70000</MinCode>
          <MaxCode>79999</MaxCode>
          <Name>Investment</Name>
        </AccountType>
        <Name>Real Estate Properties ( Australian - Residential)</Name>
        <Units>0</Units>
        <Debits>0</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Investment</Label>
          <MinCode>70000</MinCode>
          <MaxCode>79999</MaxCode>
          <Name>Investment</Name>
        </AccountType>
        <Name>Lot 4, Carters Road, Margaret River</Name>
        <Units>1</Units>
        <Debits>1600000</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>C</AccountClass>
        <AccountType>
          <Label>Investment</Label>
          <MinCode>70000</MinCode>
          <MaxCode>79999</MaxCode>
          <Name>Investment</Name>
        </AccountType>
        <Name>Shares in Listed Companies (Australian)</Name>
        <Units>0</Units>
        <Debits>0</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Investment</Label>
          <MinCode>70000</MinCode>
          <MaxCode>79999</MaxCode>
          <Name>Investment</Name>
        </AccountType>
        <Name>Bhp Billiton Limited</Name>
        <Units>4000</Units>
        <Debits>102000</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Investment</Label>
          <MinCode>70000</MinCode>
          <MaxCode>79999</MaxCode>
          <Name>Investment</Name>
        </AccountType>
        <Name>Falcon Minerals Limited - Ordinary Fully Paid</Name>
        <Units>30000</Units>
        <Debits>330</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Investment</Label>
          <MinCode>70000</MinCode>
          <MaxCode>79999</MaxCode>
          <Name>Investment</Name>
        </AccountType>
        <Name>Goconnect Limited - Ordinary Fully Paid</Name>
        <Units>250000</Units>
        <Debits>1750</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Investment</Label>
          <MinCode>70000</MinCode>
          <MaxCode>79999</MaxCode>
          <Name>Investment</Name>
        </AccountType>
        <Name>Iron Ore Holdings Limited - Ordinary Fully Paid</Name>
        <Units>15000</Units>
        <Debits>10500</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Investment</Label>
          <MinCode>70000</MinCode>
          <MaxCode>79999</MaxCode>
          <Name>Investment</Name>
        </AccountType>
        <Name>Lynas Corporation Limited - Ordinary Fully Paid</Name>
        <Units>35578</Units>
        <Debits>1351.96</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Investment</Label>
          <MinCode>70000</MinCode>
          <MaxCode>79999</MaxCode>
          <Name>Investment</Name>
        </AccountType>
        <Name>Newcrest Mining Limited</Name>
        <Units>2000</Units>
        <Debits>23680</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Investment</Label>
          <MinCode>70000</MinCode>
          <MaxCode>79999</MaxCode>
          <Name>Investment</Name>
        </AccountType>
        <Name>Norwest Energy Nl - Ordinary Fully Paid</Name>
        <Units>200000</Units>
        <Debits>1000</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Investment</Label>
          <MinCode>70000</MinCode>
          <MaxCode>79999</MaxCode>
          <Name>Investment</Name>
        </AccountType>
        <Name>Otto Energy Limited - Ordinary Fully Paid</Name>
        <Units>150000</Units>
        <Debits>10200</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Investment</Label>
          <MinCode>70000</MinCode>
          <MaxCode>79999</MaxCode>
          <Name>Investment</Name>
        </AccountType>
        <Name>OZ Minerals Ltd</Name>
        <Units>4000</Units>
        <Debits>15320</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Investment</Label>
          <MinCode>70000</MinCode>
          <MaxCode>79999</MaxCode>
          <Name>Investment</Name>
        </AccountType>
        <Name>Platinum Australia Limited - Ordinary Fully Paid</Name>
        <Units>19000</Units>
        <Debits>1273</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Investment</Label>
          <MinCode>70000</MinCode>
          <MaxCode>79999</MaxCode>
          <Name>Investment</Name>
        </AccountType>
        <Name>Rio Tinto Limited</Name>
        <Units>800</Units>
        <Debits>40960</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Investment</Label>
          <MinCode>70000</MinCode>
          <MaxCode>79999</MaxCode>
          <Name>Investment</Name>
        </AccountType>
        <Name>Regis Resources Limited - Ordinary Fully Paid</Name>
        <Units>10000</Units>
        <Debits>13500</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Investment</Label>
          <MinCode>70000</MinCode>
          <MaxCode>79999</MaxCode>
          <Name>Investment</Name>
        </AccountType>
        <Name>Regis Resources Limited - Option Expiring 31-Jan-2014</Name>
        <Units>8000</Units>
        <Debits>18000</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Investment</Label>
          <MinCode>70000</MinCode>
          <MaxCode>79999</MaxCode>
          <Name>Investment</Name>
        </AccountType>
        <Name>Tap Oil Limited</Name>
        <Units>10000</Units>
        <Debits>3400</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Investment</Label>
          <MinCode>70000</MinCode>
          <MaxCode>79999</MaxCode>
          <Name>Investment</Name>
        </AccountType>
        <Name>Telstra Corporation Ltd</Name>
        <Units>47000</Units>
        <Debits>298450</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Investment</Label>
          <MinCode>70000</MinCode>
          <MaxCode>79999</MaxCode>
          <Name>Investment</Name>
        </AccountType>
        <Name>Uranex Limited - Ordinary Fully Paid</Name>
        <Units>15000</Units>
        <Debits>2400</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Investment</Label>
          <MinCode>70000</MinCode>
          <MaxCode>79999</MaxCode>
          <Name>Investment</Name>
        </AccountType>
        <Name>Viralytics Limited - Ordinary Fully Paid</Name>
        <Units>15650</Units>
        <Debits>12207</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Investment</Label>
          <MinCode>70000</MinCode>
          <MaxCode>79999</MaxCode>
          <Name>Investment</Name>
        </AccountType>
        <Name>West African Resources Limited - Ordinary Fully Paid</Name>
        <Units>40000</Units>
        <Debits>3400</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Investment</Label>
          <MinCode>70000</MinCode>
          <MaxCode>79999</MaxCode>
          <Name>Investment</Name>
        </AccountType>
        <Name>Westpac Banking Corporation - Convertible Preference Shares</Name>
        <Units>1000</Units>
        <Debits>101500</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Investment</Label>
          <MinCode>70000</MinCode>
          <MaxCode>79999</MaxCode>
          <Name>Investment</Name>
        </AccountType>
        <Name>Woodside Petroleum</Name>
        <Units>6251</Units>
        <Debits>210096.11</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>C</AccountClass>
        <AccountType>
          <Label>Investment</Label>
          <MinCode>70000</MinCode>
          <MaxCode>79999</MaxCode>
          <Name>Investment</Name>
        </AccountType>
        <Name>Units in Unlisted Unit Trusts (Australian)</Name>
        <Units>0</Units>
        <Debits>0</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>S</AccountClass>
        <AccountType>
          <Label>Investment</Label>
          <MinCode>70000</MinCode>
          <MaxCode>79999</MaxCode>
          <Name>Investment</Name>
        </AccountType>
        <Name>Sea Pines Investment Trust</Name>
        <Units>500000</Units>
        <Debits>495100</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>N</AccountClass>
        <AccountType>
          <Label>Liability</Label>
          <MinCode>80000</MinCode>
          <MaxCode>89999</MaxCode>
          <Name>Liability</Name>
        </AccountType>
        <Name>GST Payable/Refundable</Name>
        <Units />
        <Debits>511.61</Debits>
        <Credits>0</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
      <Data>
        <AccountClass>N</AccountClass>
        <AccountType>
          <Label>Liability</Label>
          <MinCode>80000</MinCode>
          <MaxCode>89999</MaxCode>
          <Name>Liability</Name>
        </AccountType>
        <Name>Income Tax Payable/Refundable</Name>
        <Units />
        <Debits>0</Debits>
        <Credits>26860</Credits>
        <UnitsPrev>0</UnitsPrev>
        <DebitsPrev>0</DebitsPrev>
        <CreditsPrev>0</CreditsPrev>
        <BalancePrev>0</BalancePrev>
      </Data>
    </Data>
  </TrialBalance>
</root>

```
