<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo_text.svg" width="320" alt="Nest Logo" /></a>
</p>

## Description



## Installation

```bash
$ npm install
```

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Test

For testing copy your .env file to .env.test and change the port number to 3307.
With this all database based test can use the test db.

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## Database
In this project Prisma is used to connect to the database:
https://www.prisma.io/

You can find a docker-compose-db.yml in the folder "docker" to run a mariaDb locally for development.

## Test connection
The backend can be checked to see if it is running and responding via the following endpoint:
http(s)://<domain>/api/v1/system/ping

## OpenApi
http(s)://<domain>/api/

## License

Nest is [MIT licensed](LICENSE).
