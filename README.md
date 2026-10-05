<h1 align="center">
 👨‍🏫 Survey API
</h1>
<p align="center">🚀NodeJS, Typescript, TDD, DDD, Clean architecture and SOLID</p>
  
## Description
Suvery API project to stress concepts of clean architecture, hexagonal, abstraction, DDD.


## 🎲 Runing development server.

```bash

# install the dependencies:
$ yarn
# or 
$ npm install

# Run the application in development mode:
$ yarn dev
# or
$ npm run dev

# Access Rest api on: http://localhost:5050/api
# Access Swagger documentation on: http://localhost:5050/api-docs
# Access GraphQl Playground on: http://localhost:5050/graphql

```



## 🎲 Runing tests.

```bash

# Integration tests:
$ yarn test:integration

# Unit tests:
$ yarn test:unit

# All tests:
$ yarn test


```

## Principles

* Single Responsibility Principle (SRP)
* Open Closed Principle (OCP)
* Liskov Substitution Principle (LSP)
* Interface Segregation Principle (ISP)
* Dependency Inversion Principle (DIP)
* Separation of Concerns (SOC)
* Don't Repeat Yourself (DRY)
* You Aren't Gonna Need It (YAGNI)
* Keep It Simple, Silly (KISS)
* Composition Over Inheritance

## Patterns

* Factory
* Adapter
* Composite
* Decorator
* Proxy
* Dependency Injection
* Abstract Server
* Composition Root
* Builder
* Singleton

## Methodologies and Architectures

* TDD
* Clean Architecture
* DDD
* Conventional Commits
* GitFlow
* Modular Design
* Dependency Diagrams
* Use Cases
* Continuous Integration
* Continuous Delivery
* Continuous Deployment
* RestAPI
* GraphQL

## Tools

* Travis CI
* Coveralls
* Supertest
* @shelf/jest-mongodb
* Swagger
* Husky
* Lint staged

## Improviments

search by "Improviment:" in the code

* Refactory mongo helper (class 17)
* Refactory test using Http-hellpers
* Return user from authentication, inside login controller.
* Refactory makeValidation factory ./src/main/fatories
* Change tests from sut folder to ./__test folder.
* Adjust files to be coveraged in tests
* Change stub to spy, use faker on tests mock

Stub -> Type of mock wheren you return a static value from the mock.
