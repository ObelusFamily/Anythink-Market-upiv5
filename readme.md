# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Run the following from the project directory
`docker-compose up` : load Anythink's backend and frontend.
- If Docker is working correctly, the backend should be running and able to connect to your local database.
- test this by pointing your browser to http://localhost:3000/api/ping
- check the frontend and make sure it’s connected to the backend by going to http://localhost:3001/register

## Notes
make sure that you run all scripts in the next quests on one of the containers created by docker-compose up.  
Also, you can use docker exec to run commands on a running container.


