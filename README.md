💬​ Cypress, from Zero to the Cloud 🧑‍💻​

Sample project to demonstrate a cy.dataTest Cypress custom command.

## Pre-requirements

It is required to have Node.js and npm installed to run this project.

I used versions v24.15.0 and 11.12.1 of Node.js and npm, respectively. I suggest you use the same or later versions.

## Installation

Run npm install (or npm i for the short version) to install the dev dependencies.

## Tests

Note: Before running the tests, make a copy of the cypress.env.example.json file as cypress.env.json, which in the real world, you would update with valid credentials.

The cypress.env.json file is included on .gitignore and you're safe that confidential info won't be versioned.

## Desktop

Run npm test (or npm t for the short version) to run the test in headless mode.

Or, run npm run cy:open to open Cypress in interactive mode.

## Mobile

Run npm run test:mobile to run the test in headless mode on a mobile viewport.

Or, run npm run cy:open:mobile to open the Cypress App on a mobile viewport.

## Support this project

If you want to support this project, leave a ⭐.

---------

This project was created with 💚 by Arthur.