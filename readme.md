# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

!First of all clone the github repository to your local machine.
!After installing Docker run docker -v and docker-compose -v to check if docker is running as needed.
!Open a new terminal in the project root file and run docker-compose up
!Then go to the link http://localhost:3000/api/ping to check if its up and running.
!Now, it’s time to check the frontend and make sure it’s connected to the backend.
!If everything is working properly, you’ll be able to create a new user on http://localhost:3001/register