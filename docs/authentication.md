# Authentication

This API uses Bearer token authentication to secure requests.

## How Authentication Works
All requests must include an `Authorization` header with a valid token.

### Header Format
```http
Authorization: Bearer YOUR_API_TOKEN
