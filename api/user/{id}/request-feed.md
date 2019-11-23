# Request Feed for one user

Request feed for one user. The user is specified by {id}

**URL** : `/api/user/{id}/request-feed`

**Method** : `GET`

**Auth required** : NO

**Permissions required** : None

**Data constraints** : `{}`

## Success Responses

**Condition** : x5gon works

**Code** : `200 OK`

**Content** : 
```json
[
    {
        "id": 1,
        "title": "Material0",
        "description": "an intro to French",
        "language": "French",
        "provider": "ROJFake",
        "url": "www.fake.com",
        "isFlashCard": "false",
        "coverUrl": "https://cdn.framework7.io/placeholder/nature-1000x600-3.jpg",
        "like": 179
    },
    {
        "id": 1,
        "title": "Material1",
        "description": "an intro to French",
        "language": "French",
        "provider": "ROJFake",
        "url": "www.fake.com",
        "isFlashCard": "false",
        "coverUrl": "https://cdn.framework7.io/placeholder/nature-1000x600-5.jpg",
        "like": 179
    },
    {
        "id": 1,
        "title": "Material2",
        "description": "an intro to French",
        "language": "French",
        "provider": "ROJFake",
        "url": "www.fake.com",
        "isFlashCard": "false",
        "coverUrl": "https://cdn.framework7.io/placeholder/nature-1000x600-4.jpg",
        "like": 179
    },
    {
        "id": 1,
        "title": "Material3",
        "description": "an intro to French",
        "language": "French",
        "provider": "ROJFake",
        "url": "www.fake.com",
        "isFlashCard": "false",
        "coverUrl": "https://cdn.framework7.io/placeholder/nature-1000x600-6.jpg",
        "like": 179
    },
    {
        "id": 1,
        "title": "Material4",
        "description": "an intro to French",
        "language": "French",
        "provider": "ROJFake",
        "url": "www.fake.com",
        "isFlashCard": "false",
        "coverUrl": "https://cdn.framework7.io/placeholder/nature-1000x600-7.jpg",
        "like": 179
    }
]
```

## Error Responses

**Condition** : If x5gon does not work

**Code** : `400 Bad Request`

**Headers** : 

**Content** : `x5gon error1`