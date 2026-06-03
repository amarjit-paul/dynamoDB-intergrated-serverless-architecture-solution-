# DynamoDB-intergrated-serverless-architecture-solution-
Built a production ready architecture using AWS and dynamo DB

It is a close enough system used in todays real systems. 

# Architecture Flow
1. User accesses the application through CloudFront.
2. CloudFront serves the frontend files hosted in Amazon S3.
3. Frontend sends API requests to Amazon API Gateway.
4. API Gateway invokes the AWS Lambda function.
5. Lambda processes the request and stores/retrieves data from DynamoDB.
6. The response is returned to the frontend and displayed to the user.

# AWS services used -

| Service     | Purpose                             |
| ----------- | ----------------------------------- |
| CloudFront  | Global content delivery and caching |
| S3          | Frontend hosting                    |
| API Gateway | REST API endpoint                   |
| Lambda      | Serverless backend processing       |
| DynamoDB    | NoSQL database storage              |
| IAM         | Permissions and security            |


# what is it ??

A simple app using – 

1.User name enters. 
2.Data stored iin DynamoDB.
3.Response shown in UI.


# what i implemented ?

1. Hosted Frontend in S3.
2. Build backup logic in AWS Lambda.
3. Exposed Api via API Gateway.
4. Stored data in DynamoDb.
5. Secure and optimize collection using CloudFront.


# what it does ?

User enters a name --> API processed it --> data is stored --> response is returned in real time.


# Where this architecture is used :

1. SaaS applications. 
2. Scalable web platforms.
3. Startup products.
4. Global content delivery platforms.

# Deployment steps 
1. Deploy DynamoDB table
2. Create Lambda function
3. Configure API Gateway
4. Host frontend on S3
5. Connect CloudFront distribution
6. Test end-to-end workflow


# Key Features
1.Fully serverless architecture
2.No server management required
3.Scalable backend using AWS Lambda
4.Low-latency content delivery through CloudFront
5.Persistent data storage with DynamoDB
6.Pay-as-you-use pricing model

# Future Improvements
1.Add user authentication using Amazon Cognito
2.Implement HTTPS with ACM certificates
3.Add input validation and error handling
4.Store logs in CloudWatch for monitoring
5.Integrate CI/CD using GitHub Actions


# pictures showing the works 

<img width="1782" height="833" alt="image" src="https://github.com/user-attachments/assets/f3bc98ec-b2fc-4c09-b52c-bb7041c79e0b" />

1.image of the architeecture 

<img width="940" height="430" alt="image" src="https://github.com/user-attachments/assets/8159258c-a801-41de-b999-70d9b0823509" />

2. Tabel creation

<img width="940" height="434" alt="image" src="https://github.com/user-attachments/assets/268ee9c5-3b1a-4d1b-8e68-6dee077ea894" />

3. lambda function

<img width="940" height="436" alt="image" src="https://github.com/user-attachments/assets/286d81dd-a263-4bae-b88a-0b4e7e84c0d6" />

4. IAM policies

<img width="940" height="427" alt="image" src="https://github.com/user-attachments/assets/e1daa49f-dc52-4ef9-aebf-e8eff264b7ff" />

5. creation of an API

<img width="940" height="501" alt="image" src="https://github.com/user-attachments/assets/f2819b62-a0fa-470f-8a73-ea9e38a5c419" />

6. test refference

<img width="940" height="426" alt="image" src="https://github.com/user-attachments/assets/bec81a13-5fc3-4005-a8d3-115f3529a905" />

7. bucket forming as well as static provisioning.

<img width="940" height="500" alt="image" src="https://github.com/user-attachments/assets/73490246-892b-4c77-94f5-a584a0857a40" />

8. storing of name 

<img width="940" height="436" alt="image" src="https://github.com/user-attachments/assets/5b929844-50cf-4082-ac11-55b80c840c68" />

9. table 

<img width="940" height="477" alt="image" src="https://github.com/user-attachments/assets/bebd198a-3f76-4289-a0ac-10f446551dbd" />

10. ultimate output
