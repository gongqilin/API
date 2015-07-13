# Request : User Detail

<table>
    <tr>
        <td>Description</td>
        <td>Allows you to retrieve the details of the user</td>
    </tr>
    <tr>
        <td>Request URI</td>
        <td>/user/detail</td>
    </tr>
    <tr>
        <td>Method</td>
        <td>GET | POST</td>
    </tr>
</table>

### Parameters

The following parameters can be added in the http request.

<table>
    <tr>
        <th>Parameter</th>
        <th>Description</th>
        <th>Required</th>
    </tr>
    <tr>
        <td align="center">format=json <br> or <br> .json</td>
        <td>This is the default. Will return the data in JSON format</td>
        <td  align="center">Optional</td>
    </tr>
    <tr>
        <td align="center">format=xml  <br> or <br> .xml</td>
        <td>Will return the data in XML format</td>
        <td  align="center">Optional</td>
    </tr>
<table>

If the format parameter is not set, the returned result will always be JSON.

### Sample Request and Response

#### cURL Request - JSON

```javascript

curl -X POST https://api-staging.bgl360.com.au/user/detail --header "Authorization:bearer df2f0e40-606f-4311-8066-590732fd126b"

```

#### Response - JSON

```javascript

{
	"userDetail": {
		"username": "xyz@bglcorp.com.au",
		"firstName": "Ronaldinho",
		"lastName": "Assis Moreira",
		"firm": "bgltestapi1",
		"role": "Admin",
		"title": null
	}
}

```

#### cURL Request - XML

```

curl -X POST https://api-staging.bgl360.com.au/user/detail.xml --header "Authorization:bearer df2f0e40-606f-4311-8066-590732fd126b"

```

#### Response XML

```xml

<root xmlns='http://www.bglcorp.com.au'>
  <UserDetail>
    <Username>xyz@bglcorp.com.au</Username>
    <FirstName>Ronaldinho</FirstName>
    <LastName>Assis Moreira</LastName>
    <Firm>bgltestapi1</Firm>
    <Role>Admin</Role>
    <Title />
  </UserDetail>
</root>

```
