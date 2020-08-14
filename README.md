# JetBase Express.js backend for Mongo
[![Build Status](https://travis-ci.org/jetbase-io/jetbase-express-sql.svg?branch=master)](https://travis-ci.org/jetbase-io/jetbase-express-mongo)

Backend application with API

## Getting Started

### Enviroment

Use .env file for enviroment variables.

Example, .env.sample.local
```
DB_URL=mongodb://user:password@host:port/db - mongoDB link
PORT= 				- port number where server is running
JWT_SECRET= 		- secret key to generate auth tokens
```


### Installing

```
npm install
```

### Running

```
NODE_ENV=local npm run start
```
