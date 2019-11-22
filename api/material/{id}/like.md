# Like one material

Like one material. The material is specified by {id}.

**URL** : `/api/material/{id}/like`

**Method** : `POST`

**Auth required** : NO

**Permissions required** : None

**Data constraints**

Provide user.

```json
{
    "name" : "[String]"
}
```

**Data example** All fields must be sent.

```json
{
    "name" : "Jack"
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