# Restful Booker — API Test Suite

A professional Postman test suite built against the 
[Restful Booker API](https://restful-booker.herokuapp.com/apidoc).

## What this covers

- Health check verification
- Authentication — valid and invalid credentials
- Full booking lifecycle — Create, Read, Update, Delete
- Security testing — verifying unauthenticated requests are blocked
- Environment variables and request chaining
- Response time assertions on every request

## Test results

<img width="1205" height="672" alt="collection run" src="https://github.com/user-attachments/assets/52904a9e-fc94-4e2f-93e4-252d0bc3f0a1" />

## How to run

1. Import `Restful-Booker-API-Test-Suite.postman_collection.json` into Postman
2. Import `Restful-Booker-ENV.postman_environment.json` as your environment
3. Select the environment in the top right dropdown
4. Open Collection Runner and run all requests in order

> **Note:** Requests must run in sequence — each depends on data 
> created by the previous one. The auth token and booking ID are 
> automatically captured and passed between requests via 
> environment variables.

## Skills demonstrated

- API test design — happy path and negative scenarios
- Authentication testing — token generation and validation
- Request chaining via environment variables
- Security-aware testing — unauthorized access verification
- Postman Collections, Environments, and test scripts
