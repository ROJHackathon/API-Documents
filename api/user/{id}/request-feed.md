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
        "id": null,
        "title": "French I",
        "description": "an intro to French",
        "language": "French",
        "provider": "ROJFake",
        "url": "www.fake.com",
        "isFlashCard": "false",
        "like": 179
    },
    {
        "id": null,
        "title": "French II",
        "description": "an intro to French",
        "language": "French",
        "provider": "ROJFake",
        "url": "www.fake.com",
        "isFlashCard": "false",
        "like": 86
    },
    {
        "id": null,
        "title": "In a French Restaurant",
        "description": "common used sentence in a French restaurant",
        "language": "French",
        "provider": "ROJFake",
        "url": "www.fake.com",
        "isFlashCard": "false",
        "like": 57
    },
    {
        "id": null,
        "title": "French Travel Advice",
        "description": "advice for tourists",
        "language": "French",
        "provider": "ROJFake",
        "url": "www.fake.com",
        "isFlashCard": "false",
        "like": 659
    },
    {
        "id": null,
        "title": "French food",
        "description": "flash-card of various french dished",
        "language": "French",
        "provider": "ROJFake",
        "url": "www.fake.com",
        "isFlashCard": "true",
        "like": 45
    }
]
```

## Error Responses

**Condition** : If x5gon does not work

**Code** : `400 Bad Request`

**Headers** : 

**Content** : `x5gon error1`