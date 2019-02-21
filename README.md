# serverless-cqrs
CQRS pattern using AWS Lambda and friends

![CQRS Example](https://jpoley.github.io/images/cqrs.png)

Components:

API Gateway - front end API gateway
Lambda - two separate lambda functions separating read / write logic
RDS Database (with Read Replica) - simple database table
Step Functions - for Saga / Long running orchestration
SQS - for Events

