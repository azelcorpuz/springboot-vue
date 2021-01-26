# README

This is a springboot and vue application that when build (using maven),
the vue static files (assets, javascript, etc) will be hosted by the springboot application.

The `frontend` module will generate a `jar` that contains the static files.
The `backend` module is including this `frontend jar` as a dependency.

Why host static files in a springboot application?
* static files can be secured too (although not much needed)
* no need to create/run a separate server just to run the static files

# TODO
Frontend:
* [ ] add eslint
* [ ] add sample component
* [ ] add unit test
* [ ] add e2e test

Backend:
* [ ] add apis
* [ ] add logging
* [ ] add security
