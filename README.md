# API-Documents

**URL** : http://108.61.221.218:39802

### Account Related

* [Login](api/user/login.md) : `POST /api/user/login`
* [Show login status](api/user/{id}/status.md) : `GET /api/user/{id}/status`
* [Set user language](user/{id}/set-language.md) : `POST /api/user/{id}/set-language`
* [Set user preference](user/{id}/set-preference.md) : `POST /api/user/{id}/set-preference`
* [Set user email](user/{id}/set-email.md) : `POST /api/user/{id}/set-email`
* [Sign up](user/make-user.md) : `POST /api/user/make-user`
* [Get list of joined chatroom](api/user/{id}/get-chatroom.md) : `GET /api/user/{id}/get-chatroom`

### Feed Related

* [Request Feed for one user](api/user/{id}/request-feed.md) : `GET /api/user/{id}/request-feed`
* [Get search history of one user](api/user/{id}/history.md) : `GET /api/user/{id}/history`
* [Search Top Word](api/top-word.md) : `GET /api/top-word`
* [Search Material](api/search-material.md) : `GET /api/search-material`
* [Comment on one material](api/material/{id}/comment.md) `POST /api/material/{id}/comment`
* [Like one material](api/material/{id}/like.md) : `POST /api/material/{id}/like`
* [Get Number of likes of one material](api/material/{id}/get-like.md) : `GET /api/material/{id}/get-like`
* [Get Comments of one material](api/material/{id}/get-comment.md) : `GET /api/material/{id}/get-comment`
* [Get Material by id](api/material/{id}.md) : `GET /api/material/{id}`

### Translate Related

* [Translate Sentence](api/translate/sentence.md) : `POST /api/translate/sentence`
* [Translate Sentence(smart)](api/translate/sentence-smart.md): `POST /api/translate/sentence-smart`
* [Dictionary](api/dictionary.md) : `POST /api/dictionary`

### Chatroom Related

* [Get chatroom list](api/chatroom/get-list.md) : `GET /api/chatroom/get-list`
* [Create chatroom](api/chatroom/create.md) : `POST /api/chatroom/create`
* [Say something in chatroom](api/chatroom/{id}/say.md) : `POST /api/chatroom/{id}/say`
* [Get list of users in chatroom](api/chatroom/{id}/get-user.md) : `GET /api/chatroom/{id}/get-user`
* [Get active user in chatroom](api/chatroom/{id}/get-active-user.md) : `GET /api/chatroom/{id}/get-active-user`
* [Get list of messages of one chatroom](api/chatrooom/{id}/get-messages) : `GET /api/chatroom/{id}/get-messages`