# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

To setup your development environment you'll need to take the following steps:

1. Clone the repo to your local machine
2. Ensure that you have docker installed
3. Navigate to the root of the repository and run `docker compose up`
4. You should now be able to access the backend at `http://localhost:3000/api/ping` and the frontend at `http://localhost:3001/register`
5. Happy hacking!