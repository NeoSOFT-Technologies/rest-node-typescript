# Node-Typescript-Boilerplate

Skeleton for Node.js applications written in TypeScript

## Purpose

Our main purpose with this Skeleton is to start server application with node js and typescript.

Try it!! we ate happy to hear your feedback or any kind of new features.

## Common Features

- Quick start
- Integrated eslint, prettier and husky
- Common Error Handler
- Common Response Handler
- Simple and Standard scaffolding
- Followed SOLID Principles
- Based on Typescript Syntax
- Simple Enviroment Configuration
- Easily Add new feature
- Integrated winston Logger
- Production Ready Skeleton
- Follwed Production Ready Best Practices: Security
- Added only used npm modules
- Unit & Integration Test Cases

## Core NPM Modules

- [x] `express`, `@types/express`
- [x] `@types/node`
- [x] `typescript`
- [x] `dotenv`
- [x] `cors`
- [x] `helmet`
- [x] `http-status-codes`
- [x] `winston`, `@types/winston`

## Unit/Integration Test Cases Modules

- [x] `jest`
- [x] `ts-jest`
- [x] `@types/jest`
- [x] `supertest`
- [x] `@types/supertest`

## Logger Modules

- [x] `winston`
- [x] `@types/winston`

## Linter, Prettier and Husky Modules

- [x] `eslint`
- [x] `prettier`
- [x] `husky`
- [x] `eslint-config-airbnb`
- [x] `eslint-config-prettier`
- [x] `eslint-plugin-import`
- [x] `eslint-plugin-prettier`
- [x] `@typescript-eslint/eslint-plugin`
- [x] `@typescript-eslint/parser`

## Process Manager Modules

- [x] `nodemon`
## Start The application in Development Mode

- Clone the Application `git clone https://github.com/NeoSOFT-Technologies/rest-node-typescript.git`
- Install the dependencies `npm install`
- Start the application `npm start`
- Before starting make sure to creat prod environment `.env.local` file

## Run The Test Cases

- Install the dependencies `npm install`
- Start the application `npm run test`
- Before starting make sure to creat prod environment `.env.test` file

## Start The application in Production Mode

- Install the dependencies `npm install`
- Create the build `npm run build`
- Start the application `npm run start:production`
- Before starting make sure to creat prod environment `.env.prod` file

## Project Structure

| Name                              | Description |
| --------------------------------- | ----------- |
| **wiki/**                         | You can add project documentation and insructions file here |
| **src/**                          | Source files |
| **src/abstractions**              | Abstarct classes and Interfaces  |
| **src/components**                | REST API Components & Controllers  |
| **src/environments**              | Application Environments Handling utility  |
| **src/lib**                       | Reusable utilises and library source code like a logger|
| **src/middleware/**               | Express Middlewares like error handler feature |
| **.vscode/**                      | VSCode tasks, launch configuration and some other settings |
| **build/**                        | Compiled source files will be placed here |
| **tests/**                        | Test cases will be placed here |
| **tests/helpers/**                | Helpers for test cases will be placed here  |
| **tests/unit-tests/**             | Unit Test cases will be placed here  |
| **tests/integration-tests/**      | API routes (Integration) Test cases will be placed here|

## Workflow

![Workflow](https://github.com/santoshshinde2012/node-boilerplate/blob/master/wiki/boilerplate-workflow.png?raw=true)

## Default System Health Status API

- `${host}/api/system` - Return the system information in response
- `${host}/api/time` - Return the current time in response
- `${host}/api/usage` - Return the process and system memory usage in response
- `${host}/api/process` -  Return the process details in response
- `${host}/api/error` - Return the error generated object in response

## Notes

### 1. Why is my git pre-commit hook not executable by default?

- Because files are not executable by default; they must be set to be executable.

```
chmod ug+x .husky/*
chmod ug+x .git/hooks/*
```

### 2. [Production Best Practices: Security](https://expressjs.com/en/advanced/best-practice-security.html)

- Don’t use deprecated or vulnerable versions of Express
- Use TLS
- Use Helmet
- Use cookies securely
- Prevent brute-force attacks against authorization
- Ensure your dependencies are secure
- Avoid other known vulnerabilities
- Additional considerations

