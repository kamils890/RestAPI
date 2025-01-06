<!-- @format -->

# USER API Spec

## Resgister User API

Endpoint : POST /api/users

Request Body :

```json
{
  "username": "kamils",
  "password": "example123",
  "name": "Kamil Hidayat"
}
```

Response Body Succes :

```json
{
  "data": {
    "username": "kamils",
    "name": "Kamil Hidayat"
  }
}
```

Response Body Error :

```json
{
  "errors": "Username Already Registered"
}
```

## Login User API

## Update User API

## Get User API

## Logout User API
