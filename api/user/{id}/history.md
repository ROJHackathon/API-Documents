# Get search history of one user

Show search history of one user. The user is specied by {id}

**URL** : `/api/user/{id}/history`

**Method** : `GET`

**Auth required** : NO

**Permissions required** : None

**Data constraints** : `{}`

## Success Responses

**Condition** : There are no search history

**Code** : `200 OK`

**Content** : '[]'


### OR

**Condition** : There are one or more search history

**Code** : `200 OK`

**Content** :
```json
[
    "French Tutorial10",
    "French Restaurant",
    "history of French",
    "French food",
    "learning French",
    "traveling to French"
]
```

## Error Responses

**Condition** : If user id does not exist.

**Code** : `404 NOT FOUND`

**Headers** : 

**Content** : `Could not find user {id}`