# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Install docker and docker-compose
2. Check that everything is installed as expected with `docker -v` and `docker-compose -v`
3. Clone this repo
4. `cd` into this repo root and run `docker-compose`. This step might take a while.
5. Check that the [backend](http://localhost:3000/api/ping) returns 200.
6. Check the [frontend](http://localhost:3001/register) and register your own user.
