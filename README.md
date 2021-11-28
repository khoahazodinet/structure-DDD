# Final Project: Nestjs Api (Back End)

<hr /> 


### Installation
```ssh
# for npm
$ npm install

# or yarn
$ yarn install
```

### Running the app

```ssh
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```
Open http://localhost:4000/api/swagger with your browser to see the result.

### Test
```ssh
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

### Code Structure
```
.
├── README.md
├── nest-cli.json
├── package.json
├── src
│   ├── app.module.ts
│   ├── common
│   │   ├── constants.ts
│   │   └── database
│   ├── main.ts
│   │
│   ├── auth...
│   │
│   └── user
│       ├── interface
│       │   ├── user.interface.ts
│       │   └── dto
│       ├── app
│       │   ├── controllers
│       │   └── services
│       ├── domain
│       │   └── entities
│       ├── infrastructure
│       │   └── repository
│       └── user.module.ts
├── test
│   ├── app.e2e-spec.ts
│   └── jest-e2e.json
├── tsconfig.build.json
├── tsconfig.json
└── yarn.lock

```
