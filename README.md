# Cage App

NOTICE: Thse are build to be run in a docker container server

In `cage-api` and `cage-app` a `.env.example` is provided.
Copy this to `.env` and fill out the information.
The server will NOT RUN without proper environment variables

## Installation

using docker

```sh
$ docker-compose up -d
```

cage-api

```sh
$ npm install
$ npm run build
$ npm run start
```

cage-app

```sh
$ npm install
$ npm build
$npm start
```
