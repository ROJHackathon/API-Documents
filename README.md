# API-Documents


### Account Related

* [Login](api/user/login.md) : `POST /api/user/login`
* [Show login status](user/login-status.md) : `GET /api/user/login-status`
* [Set user language](user/set-language.md) : `POST /api/user/set-language`
* [Set user preference](user/set-preference.md) : `POST /api/user/set-preference`
* [Sign up](user/make-user.md) : `POST /api/user/make-user`

### Feed Related

* [Request Feed for one user](api/user/{id}/request-feed.md) : `GET /api/user/{id}/request-feed`
* [Get search history of one user](api/user/{id}/history.md) : `GET /api/user/{id}/history`
* [Search Top Word](api/top-word.md) : `GET /api/top-word`
* [Search Material](api/search-material.md) : `GET /api/search-material`
* [Comment on one material](api/material/{id}/comment.md) `POST /api/material/{id}/comment`
* [Like one material](api/material/{id}/like.md) : `POST /api/material/{id}/like`
* [Get Number of likes of one material](api/material/{id}/get-like.md) : `GET /api/material/{id}/get-like`
* [Get Comments of one material](api/material/{id}/get-comment.md) : `GET /api/material/{id}/get-comment`