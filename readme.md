# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Instructions to set up a local environment - 

**Install dependencies**
1. Install docker - https://docs.docker.com/get-docker/
2. Verify docker installation with `docker -v` and `docker-compose -v`
3. Clone this repo

**Set up**
1. Run `docker-compose up` from the project root directory
2. Verify the back-end is working by hitting http://localhost:3000/api/ping
3. Verify the front-end is working by trying to register a new user at http://localhost:3001/register
