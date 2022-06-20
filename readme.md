# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

* Install docker, and make sure it's installed using `docker -v` and `docker-compose -v`
* Run `docker-compose up` from the root of the repo
* Navigate to http://localhost:3000/api/ping to make sure it's running
* Test whether the front-end is communicated correctly with the backend by signing up in http://localhost:3001/register
