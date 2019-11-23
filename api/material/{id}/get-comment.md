# Get Comments of one material

Show comments of one material. The material is specified by {id}.

**URL** : `/api/material/{id}/get-comment`

**Method** : `GET`

**Auth required** : NO

**Permissions required** : None

**Data constraints** : `{}`

## Success Responses

**Condition** : There are not any comments for that material.

**Code** : `200 OK`

**Content** : `[]`

### OR

**Condition** : There are one or more comments for the material.

**Code** : `200 OK`

**Content** : In this example, the response contains 2 comments from "fake user 1" and "fake user 2" respectively:

```json
[
    {
        "id": null,
        "content": "Comment 1",
        "user": {
            "id": null,
            "name": "fake user 1"
        },
    },
    {
        "id": null,
        "content": "Comment 2",
        "user": {
            "id": null,
            "name": "fake user 2"
        },
    }
]
```

## Error Responses

**Condition** : If id does not exist.

**Code** : `404 NOT FOUND`

**Headers** : 

**Content** : `Could not find material {id}`
```