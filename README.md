# dintlo-exchange
The API allows you to:
- Buy and Sell dintlo token.


## Rate Limiting
You are limited to 2 requests per second per IP. Drop us an email on x@dintlo.com for requesting an increase.

## Public Enpoints

## Authentication
You can generate an API_KEY and an API_SECRET from your account settings.

## Errors
- HTTP 4XX
- HTTP 429 will be returned when rate limit is violated
- HTTP 5XX 

Response

```
{
  "message": string,
  "code": integer
}
```


## Library Client Support
- Python Client
- Go Client
