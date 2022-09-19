# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

0. Pre-requisite: Download and install [Docker](https://docs.docker.com/get-docker/)
1. Clone this repo, don't fork it!
2. CD into the folder that was just created
3. Run the command `docker-compose up`
4. Check to make sure the backend was set up correctly by hitting [this endpoint](http://localhost:3000/api/ping)
5. Check to make sure the frontend was set up correctly by creating a new user at [this endpoint](http://localhost:3000/api/ping)
