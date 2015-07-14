# API Rate Limits

In order to manage the high volume of requests, the BGL API will limit the number of requests a client can make to BGL API.  This constraints are based on two aspects, which is explained below.

#### 1. X-Rate Daily Limit


This is a value that will be enforced on the number of requests a client could make on a given day. Currently this is set to unlimtted in the staging envoirnment (https://api-staging.bgl360.com.au).

The response header will indicate the remaining number of requests available.  For every valid request we make this indicator will reduce it's count by one. Zero means we have hit the available threshold.

![logo](/images/XRateDailyLimitRemain.png "Remaining Daily Limit")

By any means if we exceed the given limit we will receive the following error.

```javascript

{
    "message": "Too Many Requests",
    "errors": [
        "You have exceeded your daily limit"
    ],
    "status": 429
}

```

Please not, that any requests that will return an error response will not reduce the daily limit threshold.

#### 2. X-Rate Limit


This is a value that indicates how many requests that could be made within a given time frame. Currently this is set to 100 per 10 minute period in the staging envoirnment (https://api-staging.bgl360.com.au).

By any mean if the client makes requests more than the specified X limit, BGL API will return an error response as follows.


```javascript

{
    "message": "Too Many Requests",
    "errors": [
        "You had too many requests in last 10 mins, the rate limit ceiling for every 10 mins is 100"
    ],
    "status": 429
}

```



