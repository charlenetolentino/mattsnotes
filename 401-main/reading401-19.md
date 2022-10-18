# AWS: Events

[Home](/README.md) | [Back](/401-main/401TableofContents.md)

Questions:

- Describe the similarities between AWS API Gateway + Lambda functions and an ExpressJS Server

  - only diffrnece is that AWS can charge you tons of money

- List the AWS Database offerings and talk about the pros and cons of each

  - automatic software pathcing and scalability

- Who’s the difference between a FIFO and a standard queue?

  - Standard queues provide at-least-once delivery, which means that each message is delivered at least once. FIFO queues provide exactly-once processing, which means that each message is delivered once and remains available until a consumer processes it and deletes it. Duplicates are not introduced into the queue.

- How can the server be assured a message was properly received?

  - create a function


Vocab:

Serverless API - API that functions on the cloud
Triggers - a set of criteria to meet to run a function
Dynamo vs Mongo - Mongo can be used anywhere, Dynamo is just for AWS
Dynamoose vs Mongoose - Dynamoose is just for AWS

Preview:

I need some tutoring on AWS
