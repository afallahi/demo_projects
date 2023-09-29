
# 1. Serverless Application with Node.js and AWS 

<div align="center">
	<a><img width="150" src="https://user-images.githubusercontent.com/25181517/183568594-85e280a7-0d7e-4d1a-9028-c8c2209e073c.png" alt="Node.js" title="Node.js"/></a>
	<a><img width="150" src="https://user-images.githubusercontent.com/25181517/183896132-54262f2e-6d98-41e3-8888-e40ab5a17326.png" alt="AWS" title="AWS"/></a>
</div>

<p align="center">
	<a><img width="60" src="https://user-images.githubusercontent.com/25181517/183890598-19a0ac2d-e88a-4005-a8df-1ee36782fde1.png" alt="TypeScript" title="TypeScript"/></a>
	<a><img width="60" src="https://user-images.githubusercontent.com/25181517/121401671-49102800-c959-11eb-9f6f-74d49a5e1774.png" alt="npm" title="npm"/></a>
	<a><img width="60" src="https://user-images.githubusercontent.com/25181517/117208740-bfb78400-adf5-11eb-97bb-09072b6bedfc.png" alt="PostgreSQL" title="PostgreSQL"/></a>
  <a><img width="60" src="https://user-images.githubusercontent.com/25181517/186711335-a3729606-5a78-4496-9a36-06efcc74f800.png" alt="Swagger" title="Swagger"/></a>
	<a><img width="60" src="https://user-images.githubusercontent.com/25181517/192109061-e138ca71-337c-4019-8d42-4792fdaa7128.png" alt="Postman" /></a>
	
</p>

## Description
[Source Code and more detailed info](https://github.com/afallahi/node-sls)

## Product Requirements

- Serverless Application
- Users can register, login and view their profile

## System Design

  ![Serverless_CodePipeline](https://github.com/afallahi/demo_projects/assets/73287428/deb60cd0-8bbc-4fba-8572-b7069e4b372f)


### Functional Requirements
- User register and login
- User verfication with OTP/SMS
  
### Non-Functional Requirements
### Database Requirements

## Tech Stack
- Node.js
- Typescript
- AWS Lambda
- Serverless Framework
- PostgreSQL
- REST API
- Docker
- AWS CodePipeline (CI/CD)
- AWS Secrets Manager

<!-- =================================================================================================================== -->

# 2. CI/CD With AWS CodePipeline and CDK TypeScript

<div align="center">
	<a><img width="150" src="https://user-images.githubusercontent.com/25181517/183568594-85e280a7-0d7e-4d1a-9028-c8c2209e073c.png" alt="Node.js" title="Node.js"/></a>
	<a><img width="150" src="https://user-images.githubusercontent.com/25181517/183896132-54262f2e-6d98-41e3-8888-e40ab5a17326.png" alt="AWS" title="AWS"/></a>
</div>

<p align="center">
	<a><img width="60" src="https://user-images.githubusercontent.com/25181517/183890598-19a0ac2d-e88a-4005-a8df-1ee36782fde1.png" alt="TypeScript" title="TypeScript"/></a>
	<a><img width="60" src="https://user-images.githubusercontent.com/25181517/121401671-49102800-c959-11eb-9f6f-74d49a5e1774.png" alt="npm" title="npm"/></a>	
</p>

## Description
[Source Code and more detailed info](https://github.com/afallahi/cdk-codepipeline)

## System Design

![CDK_CodePipeline](https://github.com/afallahi/cdk-codepipeline/assets/73287428/b27e9630-fb79-4876-946b-1cec4efc8052)


## Stack

- AWS CodePipeline
- AWS CDK
- CloudFormation
- AWS Lambda
- Node.js
- Typescript
- Jest for Unit Tests

<!-- =================================================================================================================== -->

# 3. Token-based Authentication

<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="150" alt="Nest" /></a>
  <a><image src="https://user-images.githubusercontent.com/25181517/183897015-94a058a6-b86e-4e42-a37f-bf92061753e5.png" width="150" alt="React" /></a>
</p>
<p align="center">
  <a><img src="https://user-images.githubusercontent.com/25181517/183890598-19a0ac2d-e88a-4005-a8df-1ee36782fde1.png" width="60" alt="Typescript" /></a>
  <a><img src="https://user-images.githubusercontent.com/25181517/182884177-d48a8579-2cd0-447a-b9a6-ffc7cb02560e.png" width="60" alt="Mongo" /></a>
  <a><img src="https://user-images.githubusercontent.com/25181517/186711335-a3729606-5a78-4496-9a36-06efcc74f800.png" width="60" alt="Swagger" /></a>
  <a><img src="https://user-images.githubusercontent.com/25181517/192109061-e138ca71-337c-4019-8d42-4792fdaa7128.png" width="60" alt="Postman" /></a>
  <a><img src="https://user-images.githubusercontent.com/25181517/121401671-49102800-c959-11eb-9f6f-74d49a5e1774.png" width="60" alt="npm" /></a>
</p>

[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/nestjs/nest

## Description

Users enter their username and password to obtain access token which allows them to fetch protected resources without using their credentials. Refresh token allows users to get a new access token once it's expired/invalidated. 

[Source Code and more detailed info](https://github.com/afallahi/fs-jwt)

## System Design

![Nest_JWT](https://github.com/afallahi/demo_projects/assets/73287428/ff721b82-6be5-41ce-b43b-42e68808f012)

## Stack


- NestJS
- Typescript
- Docker
- MongoDB
- Swagger (link: base_url/api)
- JWT (access token, refresh token, Passport strategies)
- Redis
- Postman
- React

<!-- =================================================================================================================== -->

# 4. Serverless Domain Driven Design with CQRS

<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="150" alt="Nest" /></a>
  <a><img src="https://user-images.githubusercontent.com/25181517/183896132-54262f2e-6d98-41e3-8888-e40ab5a17326.png" width="150" alt="AWS"</a>
</p>
<p align="center">
  <a><img src="https://user-images.githubusercontent.com/25181517/117208740-bfb78400-adf5-11eb-97bb-09072b6bedfc.png" width="60" alt="PostgreSQL" /></a>
  <a><img src="https://user-images.githubusercontent.com/25181517/183890598-19a0ac2d-e88a-4005-a8df-1ee36782fde1.png" width="60" alt="Typescript" /></a>
  <a><img src="https://user-images.githubusercontent.com/25181517/121401671-49102800-c959-11eb-9f6f-74d49a5e1774.png" width="60" alt="npm" /></a>
</p>


## Description
Basic NestJS application using CQRS which runs as local app, local cloud with Lambda using Serverless Framework and also connects to AWS RDS. 

[Source Code and more detailed info](https://github.com/afallahi/nest-cqrs-pg)

## Architecture

![CQRS](https://github.com/afallahi/demo_projects/assets/73287428/a0da249e-e6ca-4f8c-9c15-06115061df8c)

CQRS design pattern in DDD with [Nest](https://github.com/nestjs/nest), PostgreSQL, and Docker for local run and Lambda and RDS for cloud.

## Stack

- NestJS with CQRS design pattern
- Typescript
- PostgreSQL
- Docker
- AWS Lambda function behind AWS API Gateway. Single lambda serves entire API via proxy+.
- Serverless Framework
- CloudFormation
- AWS RDS

<!-- =================================================================================================================== -->

# 5. Multi-Region Serverless Architecture

<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="150" alt="Nest" /></a>
  <a><img src="https://user-images.githubusercontent.com/25181517/183896132-54262f2e-6d98-41e3-8888-e40ab5a17326.png" width="150" alt="AWS"</a>
</p>

[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/nestjs/nest

## Description
Multi-region serverless architecture with DynamoDB Global Tables, Lambda, CloudFormation, and Serverless Framework

[Source Code and more detailed info](https://github.com/afallahi/nest-ddb-mr)


## Architecture

![sls_mr_ddb](https://github.com/afallahi/demo_projects/assets/73287428/e27b7323-092a-4cfc-86d6-989981cccc00)

This is a Serverless architecture where NestJS REST APIs are implemented in AWS Lambda connected to DynamoDB NoSQL to store data. DynamoDB Global Tables replicated in multiple regions helps us to have a mult-region architecture with high availability.

## Stack


- NestJS
- AWS Lambda
- Serverless Framework
- CloudFormation
- DynamoDB Global Tables
