# Login

Login

**URL** : `/api/login`

**Method** : `POST`

**Auth required** : NO

**Permissions required** : None

**Data constraints** : 
```json
{
    "token" : [Integer]
}
```

**Data example** :
```json
{
    "token" : -1995665603
}
```

## Success Responses

**Condition** : valid token

**Code** : `200 OK`

**Content** : 
```json
{
    "message": "Logged out"
}
```

## Error Responses

**Condition** : invalid token

**Code** : `200 OK`

**Headers** : 

**Content** : 
```json
{
    "message": "Invalid token",
}
```