# Get number of likes of one material

Show number of likes of one material. The material is specified by id.

**URL** : `/api/material/{id}/get-like`

**Method** : `GET`

**Auth required** : NO

**Permissions required** : None

**Data constraints** : `{}`

## Success Responses

**Condition** : There are zero or more likes for material with id {id}.

**Code** : `200 OK`

**Content** : `183`

## Error Responses

**Condition** : If material id does not exist.

**Code** : `404 NOT FOUND`

**Headers** : 

**Content** : `Could not find material {id}`