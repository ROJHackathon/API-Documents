# API-Documents

**URL** : https://ez-talk-api-provider.azurewebsites.net

**database** : Wong1215

## User Related

* Login : `POST /api/login`
* logout : `POST /api/logout`
* register : `POST /api/register`
* Get User Info : `GET /api/user/{id}`
* Get History (fake) : `GET /api/user/{id}/history`
* Get Online Users : `GET /api/get-online-users`

## Material Related

* Get Material Info : `GET /api/material/{id}`
* Make Comment : `POST /api/material/{id}/comment`
* Get Comments : `GET /api/material/{id}/get-comments`
* Love : `POST /api/material/{id}/love`

## Chatroom Related

* Create chatroom : `POST /api/create-chatroom`
* Get Chatroom Info : `GET /api/chatroom/{id}`
* Say something : `POST /api/chatroom/{id}/say`
* Get Messages : `GET /api/chatroom/{id}/get-messages`

## Others

* Search material : `POST /api/search-material`
* Top Word (fake) : `GET /api/top-word`
