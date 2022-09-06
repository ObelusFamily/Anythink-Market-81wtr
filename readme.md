# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup
1. Clone the repo into your local machine.
2. Install **Docker** 
3. Run command ```docker-compose up``` from your project root directory.
4. If Docker is working correctly, the backend should be running and able to connect to your local database.
   Check that by hoping over your browser to http://localhost:3000/api/ping.

