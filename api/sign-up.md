# sign-up

sign-up

**URL** : `/api/sign-up`

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
**Data Example** : 
```json
{
	"userName" : "wcl",
	"password" : "wong1215"
}

```

## Success Responses

**Condition** : the user name is **NOT** used by others

**Code** : `200 OK`

**Content** : 
```json
{
    "id": 117536,
    "name": "wcl",
    "password": "wong1215",
    "avatarUrl": null,
    "email": null,
    "language": null,
    "preference": null
}

```

## Error Responses

**Condition** : user name is used by others

**Code** : `200 OK`

**Headers** : 

**Content** : 
```json
{
    "id": null,
    "name": null,
    "password": null,
    "avatarUrl": null,
    "email": null,
    "language": null,
    "preference": null
}
```