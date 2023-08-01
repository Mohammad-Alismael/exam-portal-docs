---
sidebar_position: 1
---

# Auth

this page for authentication

#### **API Endpoint**

```http
  POST /users/auth
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `username` | `string` | **Required**. username feild must be filled |
| `password` | `string` | **Required**. password feild must be filled |
#### **Request body**
```json
{
  "username": "admin",
  "password": "123"
}
```
#### **Response body**
it will return access token, along with refresh token but refresh token is stored inside http-only cookie
```json
{
  "accessToken": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VyX2lkIjoyLCJ1c2VybmFtZSI6ImFkbWluIiwicm9sZV9pZCI6IjMiLCJpYXQiOjE2OTA4Mjg2NTgsImV4cCI6MTY5MDgyOTU1OH0.pW4wsVK4fZioe-Y5e7TB7k5Q038QV_R1__ZTYX7FHrU"
}
```