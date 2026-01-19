# Smart Attendance System (AWS | Python)

## Overview

This project is a cloud-based smart attendance system that I developed to understand how serverless backend applications work on AWS. The system records attendance data through an API and stores it securely in a database without the need to manage servers.

I built this project while learning AWS and backend development, with the focus on understanding service integration rather than building a full-fledged product.

## Problem Statement

Manual attendance systems are time-consuming and error-prone. This project explores a serverless approach where attendance records can be stored efficiently and accessed in a scalable way using cloud services.

## Architecture

- **API Gateway** is used to expose REST APIs.  
- **AWS Lambda (Python)** processes attendance requests.  
- **DynamoDB** stores attendance data.  
- **IAM Roles** manage permissions securely.  

Client → API Gateway → Lambda → DynamoDB


## AWS Services Used

- **AWS Lambda**
- **API Gateway**
- **DynamoDB**
- **IAM**

## Workflow

- Attendance details are sent to the API endpoint.  
- **API Gateway** triggers the Lambda function.  
- **Lambda** validates the input and formats the data.  
- Attendance record is stored in **DynamoDB**. 
- A response is returned to confirm submission.  

## Technologies

- **Python**
- **AWS Lambda**
- **API Gateway**
- **DynamoDB**
- **IAM**

## What I Learned

- Understanding serverless architecture and event-driven design.  
- Writing backend logic using AWS Lambda in Python.  
- Managing permissions using IAM roles.  
- Working with DynamoDB for NoSQL data storage.  

This project helped me become more confident in explaining AWS backend workflows during interviews.

## Future Enhancements

- Authentication using AWS Cognito.  
- Attendance reporting and analytics.  
- Frontend dashboard integration.  
- Deployment automation using AWS SAM.  
