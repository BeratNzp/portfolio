# GG Live

## Description
An "appointment and live video customer representative" application for a premium brand affiliated with a world-renowned white
goods group based in Germany.
The application was initially developed by a world-renowned consulting firm using the Amazon Chime SDK and AWS SAM
infrastructure. However, the project later became inactive, ending its lifecycle.
Following an agreement with our client, the infrastructure and application issues were resolved, and the necessary updates and
improvements were made, and the infrastructure and application were relaunched.

## Diagram
![diagram](project.jpg)

## Tech Stack
* Node.js
* GitHub Actions
* Amazon Web Services
    * AWS SAM
    * Amazon API Gateway (RestAPI and WebSocket)
    * AWS Lambda
    * Amazon DynamoDB
    * AWS Secrets Manager
    * Amazon CloudWatch
    * Amazon SES
    * Amazon SNS with Platform Applications (for APNs)
    * Amazon S3
    * Amazon VPC with EIP (for Invoking Lambda with Static IP due to security rules)