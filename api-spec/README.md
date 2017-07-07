#Endpoints

1. `POST /api/users/login`
1. `POST /api/users`
1. `GET /api/user`
1. `PUT /api/user`
1. `GET /api/profiles/:username`
1. `POST /api/profiles/:username/follow`
1. `DELETE /api/profiles/:username/follow`
1. `GET /api/articles`
    1. `?tag=AngularJS`
    1. `?author=jake`
    1. `?favorited=jake`
    1. `?limit=20`
    1. `?offset=0`
1. `GET /api/articles/feed`
    1. `?limit=`
    1. `?offset=`
1. `GET /api/articles/:slug`
1. `POST /api/articles`
1. `PUT /api/articles/:slug`
1. `DELETE /api/articles/:slug`
1. `POST /api/articles/:slug/comments`
1. `GET /api/articles/:slug/comments`
1. `DELETE /api/articles/:slug/comments/:id`
1. `POST /api/articles/:slug/favorite`
1. `DELETE /api/articles/:slug/favorite`
1. `GET /api/tags`
