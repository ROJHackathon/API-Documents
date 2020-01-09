# API-Documents

**URL** : https://ez-talk-api-provider.azurewebsites.net
N.B. Remember to add /api-fake under test environment

**database** : Wong1215

### Account Related

* [Login](api/login.md) : `POST /api/login`
* [Log out](api/log-out.md) : `POST /api/log-out`
* [Show login status](api/user/{id}/status.md) : `POST /api/user/{id}/status`
* [Set user language](api/user/{id}/set-language.md) : `POST /api/user/{id}/set-language` (not yet)
* [Set user preference](user/set-preference.md) : `POST /api/set-preference`
* [Set user email](user/{id}/set-email.md) : `POST /api/user/{id}/set-email` (not yet)
* [Sign up](api/sign-up.md) : `POST /api/sign-up`
* [Get list of joined chatroom](api/user/{id}/get-chatroom.md) : `POST /api/user/{id}/get-chatroom` (not yet)

### Feed Related

* [Request Feed for one user](api/request-feed.md) : `GET /api/request-feed`
* [Get search history of one user](api/history.md) : `GET /api/history`
* [Search Top Word](api/top-word.md) : `GET /api/top-word`
* [Search Material](api/search-material.md) : `GET /api/search-material`
* [Comment on one material](api/material/{id}/comment.md) `POST /api/material/{id}/comment`
* [Like one material](api/material/{id}/like.md) : `POST /api/material/{id}/like`
* [Get Number of likes of one material](api/material/{id}/get-like.md) : `GET /api/material/{id}/get-like`
* [Get Comments of one material](api/material/{id}/get-comment.md) : `GET /api/material/{id}/get-comment`
* [Get Material by id](api/material/{id}.md) : `GET /api/material/{id}`

### Translate Related (not yet)

* [Translate Sentence](api/translate/sentence.md) : `POST /api/translate/sentence`
* [Translate Sentence(smart)](api/translate/sentence-smart.md): `POST /api/translate/sentence-smart`
* [Dictionary](api/dictionary.md) : `POST /api/dictionary`

### Chatroom Related (not yet)

* [Get Official Chatroom List](api/official-chatroom-list.md) : `GET /api/official-chatroom-list`
* [Get chatroom list](api/chatroom-list.md) : `GET /api/chatroom-list`
* [Create chatroom](api/create-chatroom.md) : `POST /api/create-chatroom`
* [Get specific Chatroom info](api/chatroom/{id}) : `GET /api/chatroom/{id}`
* [Say something in chatroom](api/chatroom/{id}/say.md) : `POST /api/chatroom/{id}/say`
* [Get list of users in chatroom](api/chatroom/{id}/get-user.md) : `GET /api/chatroom/{id}/get-user`
* [Get active user in chatroom](api/chatroom/{id}/get-active-user.md) : `GET /api/chatroom/{id}/get-active-user`
* [Get list of messages of one chatroom](api/chatrooom/{id}/get-messages) : `GET /api/chatroom/{id}/get-messages`
