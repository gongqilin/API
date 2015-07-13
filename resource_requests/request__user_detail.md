# Request : User Detail

<table>
    <tr>
        <td>Description</td>
        <td>Allows you to retrieve the details of the user</td>
    </tr>
    <tr>
        <td>Request URI</td>
        <td>https://api-uat.bgl360.com.au/user/detail</td>
    </tr>
    <tr>
        <td>Method</td>
        <td>GET | POST</td>
    </tr>
</table>

### Parameters


The following parameters can be added into the http request or set in the Content-Type in the header.


<table>
    <tr>
        <td align="center">format=json <br> or <br> .json</td>
        <td>This is the default. Will return the data in JSON format.</td>
        <td  align="center">Optional</td>
    </tr>
    <tr>
        <td align="center">format=xml  <br> or <br> .xml</td>
        <td>Will return the data in XML format.</td>
        <td  align="center">Optional</td>
    </tr>
<table>

### Sample Response

#### JSON

```

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

#### XML

```

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





