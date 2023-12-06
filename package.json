{
  "name": "files_manager",
  "version": "1.0.0",
  "description": "A simple file management API built with Node.js.",
  "author": "Bezaleel Olakunori <bezaleeloci@gmail.com>",
  "license": "MIT",
  "private": true,
  "main": "server.js",
  "scripts": {
    "lint": "./node_modules/.bin/eslint",
    "lint-nt": "./node_modules/.bin/eslint.cmd",
    "check-lint": "lint controllers/ libs/ middlewares/ routes/ utils/ server.js worker.js",
    "check-lint-nt": "yarn lint-nt controllers/ libs/ middlewares/ routes/ utils/ server.js worker.js",
    "start-server": "nodemon --exec babel-node --presets @babel/preset-env ./server.js",
    "start-worker": "nodemon --exec babel-node --presets @babel/preset-env ./worker.js",
    "dev": "nodemon --exec babel-node --presets @babel/preset-env",
    "test": "./node_modules/.bin/mocha --opts mocha.opts tests/**/*.js",
    "test-with-coverage": "nyc --reporter=text ./node_modules/.bin/mocha --opts mocha.opts tests/**/*.js",
    "coveralls": "nyc ./node_modules/.bin/mocha --opts mocha.opts tests/**/*.js && nyc report --reporter=text-lcov | coveralls"
  },
  "dependencies": {
    "bull": "^3.16.0",
    "chai-http": "^4.3.0",
    "dotenv": "^16.0.1",
    "express": "^4.17.1",
    "googleapis": "^101.0.0",
    "image-thumbnail": "^1.0.10",
    "mime-message": "^0.1.3",
    "mime-types": "^2.1.27",
    "mongodb": "^3.5.9",
    "redis": "^2.8.0",
    "sha1": "^1.1.1",
    "uuid": "^8.2.0"
  },
  "devDependencies": {
    "@babel/cli": "^7.8.0",
    "@babel/core": "^7.8.0",
    "@babel/node": "^7.8.0",
    "@babel/preset-env": "^7.8.2",
    "@babel/register": "^7.8.0",
    "chai": "^4.2.0",
    "chai-http": "^4.3.0",
    "coveralls": "^3.1.1",
    "eslint": "^6.4.0",
    "eslint-config-airbnb-base": "^14.0.0",
    "eslint-plugin-import": "^2.18.2",
    "eslint-plugin-jest": "^22.17.0",
    "mocha": "^6.2.2",
    "mocha-lcov-reporter": "^1.3.0",
    "nodemon": "^2.0.2",
    "nyc": "^15.1.0",
    "request": "^2.88.0",
    "sinon": "^7.5.0",
    "supertest": "^6.2.3"
  },
  "repository": {
    "type": "git",
    "url": "https://github.com/B3zaleel/alx-files_manager"
  },
  "bugs": {
    "url": "https://github.com/B3zaleel/alx-files_manager/issues"
  },
  "homepage": "https://github.com/B3zaleel/alx-files_manager/blob/main/README.md",
  "engines": {
    "node": "16.x",
    "npm": "8.x",
    "yarn": "1.x"
  }
}
