# Create User's Account

Create an Account for the authenticated User if an Account for that User does
not already exist. Each User can only have one Account.

**URL** : `/api/material/{id}/comment`

**Method** : `POST`

**Auth required** : NO

**Permissions required** : None

**Data constraints**

Provide content and the author of the comment.

```json
{
	"content" : "[String]",
	"user" :
	{
		"name" : "[String]"
	}
}
```

**Data example** All fields must be sent.

```json
{
	"content" : "Hello",
	"user" :
	{
		"name" : "Jack"
	}
}
```

## Success Response

**Condition** : If material and user are valid

**Code** : `200 OK`

**Content example**

```
"Jack : Hello"
```

## Error Responses

**Condition** : If material id does not exist.

**Code** : `404 NOT FOUND`

**Headers** : 

**Content** : `Could not find material {id}`