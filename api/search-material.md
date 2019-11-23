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
        "id": 1,
        "title": "tutorial 1",
        "description": "description 1",
        "language": "French",
        "provider": "ROJFake",
        "url": "www.fake.com",
        "isFlashCard": "false",
        "coverUrl": "https://cdn.framework7.io/placeholder/nature-1000x600-2.jpg",
        "like": 11
    },
    {
        "id": 1,
        "title": "tutorial 2",
        "description": "description 2",
        "language": "French",
        "provider": "ROJFake",
        "url": "www.fake.com",
        "isFlashCard": "false",
        "coverUrl": "https://cdn.framework7.io/placeholder/nature-1000x600-3.jpg",
        "like": 22
    },
    {
        "id": 1,
        "title": "tutorial 3",
        "description": "description 3",
        "language": "French",
        "provider": "ROJFake",
        "url": "www.fake.com",
        "isFlashCard": "false",
        "coverUrl": "https://cdn.framework7.io/placeholder/nature-1000x600-8.jpg",
        "like": 33
    },
    {
        "id": 1,
        "title": "tutorial 4",
        "description": "description 4",
        "language": "French",
        "provider": "ROJFake",
        "url": "www.fake.com",
        "isFlashCard": "false",
        "coverUrl": "https://cdn.framework7.io/placeholder/nature-1000x600-8.jpg",
        "like": 44
    },
    {
        "id": 1,
        "title": "tutorial 5",
        "description": "description 5",
        "language": "French",
        "provider": "ROJFake",
        "url": "www.fake.com",
        "isFlashCard": "false",
        "coverUrl": "https://cdn.framework7.io/placeholder/nature-1000x600-7.jpg",
        "like": 55
    },
    {
        "id": 1,
        "title": "tutorial 6",
        "description": "description 6",
        "language": "French",
        "provider": "ROJFake",
        "url": "www.fake.com",
        "isFlashCard": "false",
        "coverUrl": "https://cdn.framework7.io/placeholder/nature-1000x600-7.jpg",
        "like": 66
    }
]
```