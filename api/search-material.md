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
        "id": "39046",
        "title": "Lecture 12 - French Imperialism (Guest Lecture by Charles Keith)",
        "description": "France's colonial properties were thought of in the latter half of the nineteenth century as consolation for the bitter loss of Alsace and Lorraine to Germany. As civilian administrators came to replace military personnel in the colonies, and as more and more French settlers arrived, empire and colonialism came to play an important function in France's cultural self-presentation. World War I heralded the eventual decline of the French empire, a decline realized at the hands of the colonized subjects themselves.",
        "language": "en",
        "provider": "Videolectures.NET",
        "url": "http://hydro.ijs.si/v006/7b/pouc2qe6bc3n3qkgp64pifsla34nrohl.mov",
        "isFlashCard": "false",
        "coverUrl": "",
        "like": 0
    },
    {
        "id": "39046",
        "title": "Lecture 12 - French Imperialism (Guest Lecture by Charles Keith)",
        "description": "France's colonial properties were thought of in the latter half of the nineteenth century as consolation for the bitter loss of Alsace and Lorraine to Germany. As civilian administrators came to replace military personnel in the colonies, and as more and more French settlers arrived, empire and colonialism came to play an important function in France's cultural self-presentation. World War I heralded the eventual decline of the French empire, a decline realized at the hands of the colonized subjects themselves.",
        "language": "en",
        "provider": "Videolectures.NET",
        "url": "http://hydro.ijs.si/v006/7b/pouc2qe6bc3n3qkgp64pifsla34nrohl.mov",
        "isFlashCard": "false",
        "coverUrl": "",
        "like": 0
    }
]
```