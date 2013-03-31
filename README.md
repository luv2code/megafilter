Remember to do a recursive clone, there are submodules. If you don't the icons won't work.


I'll open-source it under MIT, BSD or GPLv2 when it works.


RESTful JSON API
----------------

> `GET /next`
Get the next article. Returns `article` and `pending` count.

> `GET /current`
Get the current article (good for first load) returns `article` and `pending` count.

> `DELETE /:id`
Discard an article from the queue. Returns `pending` count.

> `POST /:id`
Publish an article by ID from the queue (removing it). Returns `pending` count.
