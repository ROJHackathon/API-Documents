# Login

Login

**URL** : `/api/login`

**Method** : `POST`

**Auth required** : NO

**Permissions required** : None

**Data constraints** : 
```json
{
    "userName" : "[String]",
    "password" : "[String]"
}
```

**Data example** :
```json
{
    "userName" : "wcl",
    "password" : "wong1215"
}
```

## Success Responses

**Condition** : valid user name and correct password

**Code** : `200 OK`

**Content** : 
```json
{
    "message": "Login success",
    "token": -1739854608
}
```

## Error Responses

**Condition** : user name does not exist

**Code** : `200 OK`

**Headers** : 

**Content** : 
```json
{
    "message": "User Name Does Not Exist",
    "token": null
}
```

### Or

**Condition** : incorrect password

**Code** : `400 Bad Request`

**Headers** : 

**Content** : 
```json
{
    "message": "Invalid Password",
    "token": null
}
```