# Get material by id

Get material by id.

**URL** : `/api/material/{id}`

**Method** : `GET`

**Auth required** : NO

**Permissions required** : None

**Data constraints** : {}

## Success Responses

**Condition** : There exists material with id {id}

**Code** : `200 OK`

**Content** : 
```json
{
    "id": 1,
    "title": "Some Title",
    "description": "Some Description",
    "language": "Some Language",
    "provider": "Some Provider",
    "url": "Some url",
    "isFlashCard": "true/false",
    "coverUrl": "https://cdn.framework7.io/placeholder/nature-1000x600-3.jpg",
    "like": 0
}
```

## Error Responses

**Condition** : If material id does not exist.

**Code** : `404 NOT FOUND`

**Headers** : 

**Content** : `Could not find material {id}`