# Set Preference

Set Preference of one user. User is specified by token.

**URL** : `/api/set-preference`

**Method** : `POST`

**Auth required** : NO

**Permissions required** : None

**Data constraints** : 
```json
{
    "token" : "[int]",
    "preference" : "[String]"
}
```

**Data example** :
```json
{
	"token" : -1229012181,
	"preference" : "machine learning"
}
```

## Success Responses

**Condition** : valid token

**Code** : `200 OK`

**Content** : "Preference Set"

## Error Responses

**Condition** : token is invalid

**Code** : `401 Unauthorized`

**Headers** : 

**Content** : "Invalid Token"