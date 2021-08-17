authserver
==========

A simple Mongo/Express api server with authentication via JWT.
Intended as a starting point for hackathons and other projects.

Routes
------
```
POST    /users { name, password }
POST    /users/login { name, password }

GET     /users/verify   (auth required)
DELETE  /users { id }   (auth required)
```
