# API Application Type(s)

The Application Type, defines;

1. What an Application can access.
2. What is the Daily Rate Limit.
3. What is the 10mins Rate Limit.


The following table illustrates the Application/Client types that are currently supported and their role in the System.

<table>
    <tr>
        <th>Application Type</th>
        <th>Daily Rate Limit</th>
        <th>10mins Rate Limit</th>
        <th>Allowed Scopes</th>
    </tr>
    <tr>
        <td>Developer</td>
        <th>1000</th>
        <th>100</th>
        <th>developer</th>
    </tr>
    <tr>
        <td>Partner</td>
        <th>Unlimited</th>
        <th>500</th>
        <th>developer, audit, investment</th>
    </tr>
    <tr>
        <td>Paid Partner</td>
        <th>Unlimited</th>
        <th>Unlimited</th>
        <th>all scopes</th>
    </tr>
</table>
