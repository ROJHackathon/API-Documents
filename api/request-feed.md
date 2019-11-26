# Request Feed for one user

Request feed for one user. The user is specified by {id}

**URL** : `/api/user/{id}/request-feed`

**Method** : `GET`

**Auth required** : NO

**Permissions required** : None

**Data constraints** : ?page=[int]&token=[int]

the page parameter is optional and the default value is 1



## Success Responses

**Condition** : token is valid

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
        "coverUrl": "https://cdn.framework7.io/placeholder/nature-1000x600-5.jpg",
        "like": 0
    },
    {
        "id": "11567",
        "title": "Lecture 4 - A Nation? Peasants, Language, and French Identity",
        "description": "The problematic question of when people in France began to consider themselves part of a French nation, with a specifically French national identity, has often been explained in terms of the modernizing progress of the French language at the expense of regional dialects. In fact, the development of French identity in rural France can be seen to have taken place alongside a continued tradition of local cultural practices, particularly in the form of patois. French identity must be understood in terms of the relationship between the official discourse of the metropolitan center and the unique practices of the country's regions, rather than in terms of the unambiguous triumph of the former over the latter.",
        "language": "en",
        "provider": "Videolectures.NET",
        "url": "http://hydro.ijs.si/v006/33/gpcwb6josr56v3nbir2fd63pcam2lexz.mov",
        "isFlashCard": "false",
        "coverUrl": "https://cdn.framework7.io/placeholder/nature-1000x600-6.jpg",
        "like": 0
    }
]
```

## Error Responses

**Condition** : If x5gon does not work

**Code** : `400 Bad Request`

**Headers** : 

**Content** : `x5gon error1`