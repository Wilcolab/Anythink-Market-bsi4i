# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

- Run `docker-compose up` on your terminal to run Anythink's backend and frontend. Once docker-compose finishes loading up, the backend should be running and able to connect to the database
- Test this by pointing your browser to this link: https://obelusfamily-anythink-market-bsi4i-w5xg4jvp5qrc56jg-3000.preview.app.github.dev/ (You should see a success message if the backend is running)
- To access the frontend and make sure it's connected to the backend, click this link: https://obelusfamily-anythink-market-bsi4i-w5xg4jvp5qrc56jg-3001.preview.app.github.dev/register
- Create a new user on the page that loads.

