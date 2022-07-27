# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Clone the repo on your computer
2. Go to the docker website and install Docker Desktop
3. Verify your docker setup by running the following commands:
  - `docker -v`
  - `docker-compose -v`
4. Go to the root directory of the repo and load Anythink's backend and frontend by running the following command: `docker-compose up`
5. To verify that the *backend* is up, open the following url in your browser:  http://localhost:3000/api/ping
6. To verify that the *frontend* is working propertly, *create a new user* on http://localhost:3001/register
