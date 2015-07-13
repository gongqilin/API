# Request : User Detail

|  |  |
| -- | -- |
| Description | Allows you to retrieve the details of the user  |
| Sample Request| https://api-uat.bgl360.com.au/user/detail |
| Method support | GET, POST|

### Parameters


The following parameters can be added into the http request or set in the Content-Type in the header.

|  |  |
| :--: | -- |
| format=json <br> or <br> .json | This is the default. Will return the data in JSON format. |
| format=xml  <br> or <br> .xml | Will return the data in XML format. |

If the format parameter is not set, the returned result will always be JSON.

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





