# ctc-fall-2021-boilerplate

> This backend tutorial was based on the boilerplate developed by USC Code the Change! Thank you to all the developers who contributed to it over the years :)

## Table of Contents
- [Overview](#overview)
- [Setting Up Your Development Environment](#setting-up-your-development-environment)
- [Development](#development)
- [Testing](#testing)

## Overview

### Welcome to the CTC x AthenaHacks Backend Development Tutorial 🎉

This boilerplate has a and `backend/` directories, which contains an Express API server.

Here are some of the technologies used in this boilerplate (along with links to docs!):
### Whole repo
* [Typescript](https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes.html) - Javascript but with types...much better autocomplete & debugging
* [NodeJS](https://nodejs.org/en/) - a runtime for JS that lets you run JS on the server, your laptop, or any other computing environment

### Backend
* [Express](https://expressjs.com/en/starter/hello-world.html) - web app framework for JS that we use for our API
* [Sequelize](https://sequelize.org/master/manual/getting-started.html) - ORM for NodeJS that we use to interface with our database
* [sequelize-typescript](https://github.com/RobinBuschmann/sequelize-typescript) - makes it easier to use Typescript with Sequelize
* [express-validator](https://express-validator.github.io/docs/) - middlewares for express that validate requests
* [Postgres](https://www.postgresql.org/docs/) - open source SQL database that is awesome


## Setting Up Your Local Environment

We recommend using [Visual Studio Code](https://code.visualstudio.com/) for your development environment.  


### Mac

1. Install XCode and the XCode Command Line Tools using `xcode-select --install`
2. Install [Homebrew](https://brew.sh)
3. Install Node.js and npm via Homebrew `brew install node`
4. Install Yarn (npm++) via Homebrew using `brew install yarn`
5. Install PostgreSQL via Homebrew using `brew install postgresql`
6. Clone this repository to a local directory on your computer (`git clone <repo_url> <dir>`)
7. `cd <dir>/backend` and run `yarn install`, which will install all NPM packages specified by the `package.json` located in the backend directory of this repository

### Windows

1. Install [WSL](https://docs.microsoft.com/en-us/windows/wsl/install)
2. Install Node.js, npm, and Yarn using WSL following [these instructions](https://harshityadav95.medium.com/setting-up-nodejs-yarn-on-wsl-windows-subsystem-for-linux-e29d952ff6eb)
3. Install PostgresSQL following [these instructions](https://harshityadav95.medium.com/postgresql-in-windows-subsystem-for-linux-wsl-6dc751ac1ff3)
4. Clone this repository to a local directory on your computer (`git clone <repo_url> <dir>`)
5. `cd <dir>/backend` and run `yarn install`, which will install all NPM packages specified by the `package.json` located in the backend directory of this repository

## Development

If you look inside `package.json`, you'll see a key called `scripts`. Yarn allows you to run these scripts in Terminal using the `yarn run <script_name>` format. There are a bunch of scripts set up that will allow you to build the server for production, run the server or client in development mode, and test/lint the server (and soon, the client).

## Commands
### Backend

❗️ Make sure Postgres is running before doing anything on the backend!

Navigate into the `backend` directory and run:

1. `yarn start` to start the server
2. `yarn test` to run backend tests
3. `yarn lint` to fix your ESLint errors

*See the README in the backend directory*



