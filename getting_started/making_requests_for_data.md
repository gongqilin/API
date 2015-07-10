# Making requests for data

This section explains on how we could obtain data from the BGL API.

In order for the client to make a request for the data, the client needs to have a valid access token.  Once the client has a valid access token, the client could use the following url to make the request for data.

| Request Type | URL |
| -- | -- |
| POST/GET |  https://api-uat.bgl360.com.au/fund/list |

The above url will return the list of all available funds.  There are different variations in retrieving data.  This will be explained in detail in the next section.

However, the client needs to pass in the access token and token type as header information in the request, as per the following table

| Header Variable Name | Value | Example |
| -- | -- |
| Authorization | {token_type} {access_token} | bearer df2f0e40-606f-4311-8066-590732fd126b |

By any mean if the client passes an invalid access token or an invalid token type, the BGL API will provide an error, which is illustrated in the below table.


| Cause | Description | Error | Error Description |
| -- | -- | :--: | :--: |
| Invalid Access Token | When an invalid or expired Access token is set in header | INVALID_TOKEN |Invalid access token: {passed access token} |
| Invalid Token Type | When an invalid token type is set in header | INVALID_TOKEN |Invalid access token: {passed access token} |

