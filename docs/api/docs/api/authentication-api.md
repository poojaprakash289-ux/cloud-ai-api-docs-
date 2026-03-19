# Authentication API Reference

This document provides details for the Authentication API, including endpoints, request/response formats, and error codes.

## Endpoints
- **POST /login** – Authenticate user credentials  
- **POST /refresh** – Refresh access token  
- **POST /logout** – End user session  

## Request Example
```json
POST /login
{
  "username": "user@example.com",
  "password": "securePassword123"
}
