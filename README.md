## Testing

[![license: MIT](https://img.shields.io/badge/license-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A web-based quiz application built with React, TypeScript, and Node.js, featuring multiple choice questions, a backend server to serve quiz data, and end-to-end tests using Cypress.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Technology](#technology)
- [License](#license)
- [Walkthrough](#walkthrough)
- [Contact](#contact)

## Features

10-question quiz with scoring
Random questions from a MongoDB database
Responsive UI with Bootstrap
Restartable quiz session
Cypress-powered testing:
Component tests for Quiz UI logic
E2E tests covering full user flow

## Installation

1. Clone the repo since youre here I assume you have it, but just in case

   https://github.com/TiffanyMClark/Testing

click the <> code button and in your terminal git clone with the ssh.

2. right click the package.json in the root ( main folder ) and open it in the terminal

   npm install

3. Still in your terminal

   npm i cypress

   This will install cypress if it didn't install with

   npm i
   ( just in case )

4. Still in your terminal

   npm run build

   This will build your files ( dist ) which it will look for.

5. Still in the terminal we need to run the back end before we start testing

npm run start:dev

open the link [local](http://localhost:3000)

6. right click on the same package.json in the root and open a new terminal WHILE the other is still running and type

npm run test

You can see the test running as you click through the questions on the link above.

## Technology

Frontend: React, TypeScript, Vite

Backend: Node.js, Express, MongoDB

Testing: Cypress for end-to-end and component testing (E2E)

Database: MongoDB (with seeded data)

## license

MIT

## Walkthrough

https://app.screencastify.com/v3/watch/gAI6BRZ05abNWf551Ucr

## Contact

https://github.com/TiffanyMClark

to contact or view all of my repositories
