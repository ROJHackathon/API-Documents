# API-Documents

**URL** : https://ez-talk-api-provider.azurewebsites.net

**database** : Wong1215

## User Related

* Get User By Token : `GET /api/get-user/{token}`
* Login : `POST /api/login`
* logout : `POST /api/logout`
* register : `POST /api/register`
* Get User Info : `GET /api/user/{id}`
* Get History (fake) : `GET /api/user/{id}/history`
* Get Online Users : `GET /api/get-online-users`
* Set Preference : `POST /api/set-preference`
* Set Email : `POST /api/set-email`
* Set Language : `POST /api/set-language`
* Set Target Lanuguage : `POST /api/set-target-language`

## Material Related

* Get Material Info : `GET /api/material/{id}`
* Make Comment : `POST /api/material/{id}/comment`
* Get Comments : `GET /api/material/{id}/get-comments`
* Love : `POST /api/material/{id}/love`
* Rate : `POST /api/material/{id}/rate`

## Chatroom Related

* Get list of chatrooms : `GET /api/chatroom-list`
* Create chatroom : `POST /api/create-chatroom`
* Get Chatroom Info : `GET /api/chatroom/{id}`
* Say something : `POST /api/chatroom/{id}/say`
* Get Messages : `GET /api/chatroom/{id}/get-messages`

## Others

* Search material : `POST /api/search-material`
* Top Word (fake) : `GET /api/top-word`
* Feed : `POST /api/feed`
