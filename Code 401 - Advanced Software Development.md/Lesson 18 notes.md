# AWS: API, Dynamo, and Lambda

### AWS API Gateway Overview

1. What is Amazon API Gateway?

* "A managed service that allows developers to define the HTTP endpoints of a REST API or a WebSocket API and connect those endpoints with the corresponding backend business logic. It also handles authentication, access control, monitoring, and tracing of API requests."

2. Why is Amazon API Gateway an important part of the Serverless ecosystem?

* "Being able to trigger the execution of a serverless function directly in response to an HTTP request is the key reason why API gateway is so valuable in Serverless setups"

3. How does API Gateway integrate with other AWS services?

* Invoking an AWS Lambda function
* Invoking another HTTP endpoint, with or without VPC Link
* Returning a mock response generated within API Gateway without calling out to other services.

### AWS API Gateway

1. What are some benefits of using Amazon API Gateway?

* Effecient API Development
* Performance at any scale
* Cost savings at scale
* Easy monitoring
* Flexible security controls
* RESTful API options

2. What two API types might you choose from?

* RESTful 
* Websocket APIs

### AWS DynamoDB Guide

1. What is DynamoDB?

* "A hosted NoSQL database offered by Amazon Web Services offering reliable performance at scale, a managed experience, and a small API.

2. Under what circumstances would you recommend DynamoDB over MongoDB?

* If you need more scalability, I would recommend DynamoDB over MongoDB. Also DynamoDB is serverless compared to MongoDB, but maybe you need something more fixed. In that case, I would recommend MongoDB. Personally it feels like Dynamo offers everything that Mongo does but better.

### AWS DynamoDB 

1. Explain to a non-technical friend how DynamoDB works

* DynamoDB is like if you had to organize a wedding by yourself on a normal basis, and then suddenly all you had to do was give the instructions for how you wanted the wedding to be set up to a separate entity that handles the setup for you. You have to follow specific rules but generally it should work out ok.

### Dynamoose 

1. What is Dynamoose?

* "Dynamoose is a modeling tool for Amazon's DynamoDB. Dynamoose is heavily inspired by Mongoose, which means if you are coming from Mongoose the syntax will be very familiar."

2. What are some key features of Dynamoose?

* Type safety
* High level API
* Easy to use syntax
* DynamoDB Single Table Design Support
* Ability to transform data before saving or retrieving items
* Strict data modeling
* Support for DynamoDB Transactions
* Powerful Conditional/Filtering support
* Callback and Promise support
* AWS Multi-Region Support