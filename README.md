# dintlo-exchange
This doccumentation is intended for developers.

The API allows you to:
- Buy and Sell dintlo token.
- 


## Rate Limiting
Every endpoint is rate limited. You are limited to 2 requests per second per IP. Drop us an email on x@dintlo.com for requesting an increase.

## Public Enpoints

## Authentication
You can generate an API_KEY and an API_SECRET from your account settings.

## Features
### Orders

### Balances

### Withdrawals

### Tokens

## Errors
- HTTP 401 Unauthorized 
- HTTP 429 Will be returned when rate limit is violated
- HTTP 503 Temporarily offline
- 

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
