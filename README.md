# Files Manager

[![Coverage Status](https://coveralls.io/repos/github/B3zaleel/alx-files_manager/badge.svg?branch=main)](https://coveralls.io/github/B3zaleel/alx-files_manager?branch=main)

A simple file management API built with Express, MongoDB, Redis, Bull, and Node.js.

## Requirements

### Applications

+ Node.js
+ Yarn (the package manager/resource negotiator)

### APIs

+ A Google API should be created with at least an email sending scope and a valid URL (e.g.; `http://localhost:5000/`) should be one of the redirect URIs. The `credentials.json` file should be stored in the root directory of this project.

### Environment Variables

The required environment variables should be stored in a file named `.env` and each line should have the format `Name=Value`. The table below lists the environment variables that will be used by this server:

| Name | Required | Description |
|:-|:-|:-|
| GOOGLE_MAIL_SENDER | Yes | The email address of the account responsible for sending emails to users. |
| PORT | No (Default: `5000`)| The port the server should listen at. |
| DB_HOST | No (Default: `localhost`)| The database host. |
| DB_PORT | No (Default: `27017`)| The database port. |
| DB_DATABASE | No (Default: `files_manager`)| The database name. |
| FOLDER_PATH | No (Default: `/tmp/files_manager` (Linux, Mac OS X) & `%TEMP%/files_manager` (Windows)) | The local folder where files are saved. |

## Installation

+ Clone this repository and switch to the cloned repository's directory.
+ Install the packages using `yarn install` or `npm install`.

## Usage

Start the Redis and MongoDB services on your system and run `yarn start-server` or `npm run start-server`.

## Tests

+ Create a separate `.env` file for the tests named `.env.test` and store the value of the environment variables for the testing event in it.
+ Run `yarn test` or `npm run test` to execute the E2E tests.

## Documentation

+ TODO: Generate OpenAPI documentation with [**apidoc**](https://www.npmjs.com/package/apidoc).

## RESOURCES
+ [x] [Node JS getting started](https://intranet.alxswe.com/rltoken/8jNm2s_LfVKMqR3vHLn_uw)
+ [x] [Process API doc](https://intranet.alxswe.com/rltoken/uYPplj2cPK8pcP0LtV6RuA)
+ [x] [Express getting started](https://intranet.alxswe.com/rltoken/SujfeWKCWmUMomfETjETEg)
+ [x] [Mocha documentation](https://intranet.alxswe.com/rltoken/FzEwplmoZiyGvkgKllZNJw)
+ [x] [Nodemon documentation](https://intranet.alxswe.com/rltoken/pdNNTX0OLugbhxvP3sLgOw)
+ [x] [MongoDB](https://intranet.alxswe.com/rltoken/g1x7y_3GskzVAJBTXcSjmA)
+ [x] [Bull](https://intranet.alxswe.com/rltoken/NkHBpGrxnd0sK_fDPMbihg)
+ [x] [Image thumbnail](https://intranet.alxswe.com/rltoken/KX6cck2nyLpQOTDMLcwxLg)
+ [x] [Mime-Types](https://intranet.alxswe.com/rltoken/j9B0Kc-4HDKLUe88ShbOjQ)
+ [x] [Redis](https://intranet.alxswe.com/rltoken/nqwKRszO8Tkj_ZWW1EFwGw)      
