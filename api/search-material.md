# Search material

Search material

**URL** : `/api/search-material`

**Method** : `POST`

**Auth required** : NO

**Permissions required** : None

**Data constraints** : 
```json
{
	"text": "[String]"
}
```
**Data example**:
```json
{
	"text": "French tutorial"
}
```

## Success Responses

**Condition** : 

**Code** : `200 OK`

**Content** : 
```json
[
    {
        "id": null,
        "title": "tutorial 1",
        "description": "description 1",
        "language": "French",
        "provider": "ROJFake",
        "url": "www.fake.com",
        "isFlashCard": "false",
        "like": 11
    },
    {
        "id": null,
        "title": "tutorial 2",
        "description": "description 2",
        "language": "French",
        "provider": "ROJFake",
        "url": "www.fake.com",
        "isFlashCard": "false",
        "like": 22
    },
    {
        "id": null,
        "title": "tutorial 3",
        "description": "description 3",
        "language": "French",
        "provider": "ROJFake",
        "url": "www.fake.com",
        "isFlashCard": "false",
        "like": 33
    },
    {
        "id": null,
        "title": "tutorial 4",
        "description": "description 4",
        "language": "French",
        "provider": "ROJFake",
        "url": "www.fake.com",
        "isFlashCard": "false",
        "like": 44
    },
    {
        "id": null,
        "title": "tutorial 5",
        "description": "description 5",
        "language": "French",
        "provider": "ROJFake",
        "url": "www.fake.com",
        "isFlashCard": "false",
        "like": 55
    },
    {
        "id": null,
        "title": "tutorial 6",
        "description": "description 6",
        "language": "French",
        "provider": "ROJFake",
        "url": "www.fake.com",
        "isFlashCard": "false",
        "like": 66
    }
]
```