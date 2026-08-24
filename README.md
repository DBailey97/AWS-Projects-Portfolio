# AWS Solutions: A Portfolio of Cloud Projects ☁️
Welcome to my AWS Project Portfolio! This repository features a collection of projects that demonstrate various AWS services and solutions, offering hands-on experience from foundational concepts to advanced architectures.

## Level 1 (Introductory Projects)
This section features projects ideal for beginners, focusing on fundamental AWS concepts and basic services.
- **Project 1**: Create Three Billing Alarms
  - **Description**: This project involves configuring three AWS billing alarms to monitor and manage AWS costs effectively.
  - **Objectives**:
  * Create a billing alarm for $5
  * Create a billing alarm for $25
  * Create a billing alarm for $100
  - **Service Used**: 

- **Project 2**: Create a Cost Budget
  - **Description**: Set up a cost budget in AWS to track and manage spending.
  - **Objectives**: Create a cost budget to monitor spending
  - **Service Used**: 

- **Project 3**: Launch a Hello World Website on the Internet
  - **Description**: Deploy a simple "Hello World" website on an AWS EC2 instance to understand the process of launching and configuring an EC2 instance and making a basic web application available on the Internet.
  - **Service Used**: 

- **Project 4**: Push a Docker Image to Amazon ECR Repository
  - **Description**: Build a Docker image and push it to an Amazon ECR repository. This includes creating the repository, tagging the image, and using AWS CLI to authenticate and upload the image.
  - **Service Used**: 

- **Project 5**:  Creating an Amazon RDS DB Instance (MS SQL Server)
  - **Description**: Set up and configure a Microsoft SQL Server database instance using Amazon RDS. This includes choosing the appropriate instance type, configuring security settings, setting up backups and maintenance windows, and ensuring high availability.
  - **Service Used**: 

- **Project 6**:  Create a DynamoDB Table
  - **Description**: This project involved creating a DynamoDB table with provisioned capacity. Three random items were inserted into the table. A scan operation was performed to retrieve all items, and a query operation was used to fetch a single item based on specific criteria.
  - **Service Used**: 
 
- **Project 7**:  Install & Configure AWS CLI then Create an S3 Bucket
  - **Description**: This project involves setting up AWS CLI on your local machine, configuring it with your AWS credentials, and using it to create, list, and delete an S3 bucket. This process ensures that you can interact with AWS services programmatically and manage your S3 resources effectively.
  - **Service Used**: 

- **Project 8**:  Create an S3 Bucket and store an object in it
  - **Description**: This project involves creating an Amazon S3 bucket using the AWS Management Console and uploading a file into the bucket. Amazon S3 (Simple Storage Service) is used to store and retrieve any amount of data at any time, and this project demonstrates the basic steps of setting up and using S3 for storage.
  - **Service Used**: 

- **Project 9**:  Introduction to SNS (Simple Notification Service)
  - **Description**: This project involves creating an Amazon SNS (Simple Notification Service) topic, subscribing an email address to the topic, and confirming the subscription through the email. After confirming, a test message is sent through the SNS topic to verify that the email address receives the notification, demonstrating the basic functionality and setup of SNS for sending notifications.
  - **Service Used**: 

- **Project 10**:  Create a Lambda Function to Add Two Numbers
  - **Description**: Developed an AWS Lambda function using Python that takes two numbers as input, adds them together, and returns the result. The function also print the result out in the logs.
  - **Service Used**: 

- **Project 11**:  Host a Simple Static Webpage with S3 and CloudFront
  - **Description**: Set up an S3 bucket to host a static webpage and uploaded the webpage content. Configured an Amazon CloudFront distribution to use the S3 bucket as its origin, ensuring that the webpage content is accessible only through the CloudFront endpoint to enhance security and performance.
  - **Service Used**: 

- **Project 12**:  Create an IAM User
  - **Description**: Configured IAM by creating a new user with console access and adding it to a newly created group named "adminsGroup" with `AdministratorAccess` permissions. Enabled multi-factor authentication (MFA) for the root user and applied a password policy to enforce security best practices.
  - **Service Used**:
    
 - **Project 13**:  Use a Managed Config Rule
    - **Description**: Implemented and monitored an AWS Config rule to ensure compliance with encryption policies for EBS volumes. Enabled AWS Config in the US-EAST-1 region, selected the managed Config rule `encrypted-volumes`, and launched an EC2 instance with an unencrypted EBS volume to verify that the Config rule detects non-compliance.
    - **Service Used**:
    
- **Project 14**:  Deploy a CloudFormation Template from the AWS Console
  - **Description**: Downloaded a pre-made CloudFormation template and used it to create a CloudFormation stack. Monitored the deployment process through the events tab, confirmed the creation of a DynamoDB table and an S3 bucket, and then deleted the stack to ensure both resources were removed as part of the cleanup.
  - **Service Used**: 
    
## Level 2 (Intermediate Projects)
These projects are intended for individuals with a basic AWS understanding who wish to explore more advanced scenarios.

- **Project 1**: Create an Auto Scaling Group

  - **Description**: Configured an Auto Scaling Group (ASG) with a launch configuration that automatically scales between 2 and 5 EC2 instances. Monitored the ASG’s behavior by manually terminating an instance and observing how the ASG maintains the desired capacity. Also, adjusted the desired number of instances and explored scaling policies based on CloudWatch metrics.
  - **Services Used**: 

- **Project 2**: Deploy a Docker Container Image on AWS Fargate
  
  - **Description**: Deployed a Docker container image on AWS Fargate by configuring a container with a Docker image, setting up a task definition, defining a service, and deploying it on an ECS cluster. Explored memory limits, task roles, load balancers, and security group configurations.
  - **Services Used**: 

- **Project 3**: Create an Aurora RDS Database
  
  - **Description**: Created an Aurora RDS database with MySQL compatibility. Configured a security group to allow public access for testing purposes, set up the database using `db.r5.large` instance type, and connected to the instance using MySQL Workbench. Verified functionality by creating a test table, then deleted the database and ensured proper resource cleanup.
  - **Services Used**: 
 
- **Project 4**: Setup a Simple State Machine with at least 2 Steps
  - **Description**: Created a simple AWS Step Functions state machine consisting of two AWS Lambda functions. The first function adds two numbers provided as input, and the second function returns the square of the sum. The state machine coordinates the flow between these two Lambdas. After successfully executing the workflow, I verified the output and cleaned up the resources.
  - **Services Used**: 
 
- **Project 5**: Create a Serverless API  
  - **Description**: Developed a serverless API using AWS Lambda and API Gateway. The Lambda function responds with the message 'Hello Serverless World!'. An API Gateway was created to expose the Lambda function as an HTTP endpoint, and the API was secured using an API Key. The API endpoint was successfully tested using POSTMAN to verify both functionality and security.  
  - **Services Used**: 
 
- **Project 6**: Create a CloudWatch Alarm  
    - **Description**: Configured a CloudWatch Alarm to monitor EC2 NetworkIn traffic. An EC2 instance was launched with a simple Apache web server installed via UserData. The CloudWatch Alarm was set up to monitor the **NetworkIn** metric, with a 5-minute evaluation period and a low static threshold of 5000 bytes. The alarm was triggered by generating traffic to the instance, ensuring the monitoring setup was functional and reliable.
    - **Services Used**: 
 
- **Project 7**: Create a new CMK in KMS and encrypt an object
  - **Description**: Created a **Customer Master Key (CMK)** using AWS Key Management Service (KMS) to ensure secure encryption of an object uploaded to an S3 bucket. The object was encrypted using the custom CMK, enhancing data security and encryption at rest. Key management and access control were configured for this setup, ensuring only authorized users could interact with the encrypted object.
  - **Services Used**: 

- **Project 8**:  Create an EFS Shared File System

  - **Description**: Set up an Amazon Elastic File System (EFS) to provide a shared file system across multiple Amazon EC2 instances in separate Availability Zones within the same region.
  - **Service Used**: 

## Level 3 (Advanced Projects)
Projects at this level are designed for individuals with extensive AWS experience, featuring intricate architectures and integrations.

- **Project 1**:  SQLServer Native Backup and Restore on RDS

  - **Description**: Implemented SQL Server backup and restore on AWS RDS involving Amazon S3 bucket.
  - **Service Used**: 

- **Project 2**:  Deploy a VPC with Terraform

  - **Description**: Created Virtual Private Cloud (VPC), route tables (both public and private), route table associations, an internet gateway, an Elastic IP, and a NAT gateway and EC2 instance in both a public and a private subnet using Terraform (IaC)
  - **Service Used**: 

## Level 4 (Expert Projects)
These projects are the most challenging, demonstrating advanced AWS solutions and best practices.

- **Project 1**:  Create a Cluster of Virtual Machines Using Docker Swarm

  - **Description**: Set up a Docker Swarm cluster across five EC2 instances, with one manager node and four worker nodes, and tested it by deploying an Nginx service.
  - **Service Used**: 

- **Project 2**:  Build a Basic Web Application

  - **Description**: This project involves building a full-stack web application using AWS Amplify. It features a simple React frontend with user authentication, a serverless function to handle user sign-ups, and a DynamoDB database for storing user emails. The application leverages AWS’s robust and scalable cloud services to deliver a seamless user experience, allowing users to sign up, log in, and store information securely.
  - **Service Used**: 

 - **Project 3**:  Build a Serverless Recipe Generator with AWS Amplify and Amazon Bedrock
   - **Description**: In this project, I built a serverless web application using AWS Amplify, integrated with Amazon Bedrock and the Claude 3 Sonnet foundation model for Generative AI. The application allows users to enter a list of ingredients, and in return, it generates creative and delicious recipes powered by AI. The front end is hosted on AWS Amplify, offering continuous deployment, while the backend handles requests to generate recipes from a list of ingredients. AWS services like Cognito for authentication, AppSync for API management, and Lambda for serverless functions are used to power the app.
    - **Service Used**: 

- **Project 4**:  Building with Generative AI on AWS using PartyRock, Amazon Bedrock, and Amazon Q

    - **Description**: In this project, I worked on three independent projects using Amazon Bedrock and PartyRock:
      -  Using PartyRock, I quickly built a book recommendation app that generates personalized suggestions based on the user’s mood and allows for an interactive chatbot experience. This no-code tool made it easy to create and deploy a simple app without writing a single line of code.
      -  In Amazon Bedrock, I experimented with powerful foundation models like Claude 3 Sonnet for chat, Amazon Titan for text generation, and Titan Image Generator for creating images from text prompts. This step showed me how to integrate AI models for more creative and dynamic use cases in real-world applications.
      -  Lastly, I implemented a document-based AI model that retrieves and uses context to answer questions. I set up embeddings using Amazon Titan, performed similarity searches with FAISS, and used the Claude 3 Sonnet model to generate accurate, context-based responses to user queries. This showcased how to build applications that not only generate content but also pull in relevant information from external sources.

    - **Service Used**: 

- **Project 5**:  Multi-Tier, Highly Available, Fault-Tolerant Web Application

  - **Description**: In this project, I designed and implemented a multi-tier, highly available, and fault-tolerant web application using various AWS services including Amazon VPC, Amazon EC2, Amazon Aurora, and Amazon S3. This architecture ensures scalability, resilience, and efficient resource management. This experience is part of my journey to becoming a Cloud Engineer, focusing on building robust cloud-based applications.
  - **Service Used**:

- **Project 6**:  Building a Highly Available WordPress Web Application

  - **Description**: In this project, I designed and implemented a highly available WordPress web application on AWS using various services, including Amazon VPC, Amazon RDS, Amazon EFS, and Amazon EC2 with Auto Scaling and Application Load Balancer (ALB). This architecture ensures scalability, resilience, and efficient resource management.
  - **Service Used**:

- **Project 7**:  Create a Continuous Delivery Pipeline

  - **Description**: In this project, I created a continuous delivery pipeline using AWS services, including AWS Elastic Beanstalk, AWS CodeBuild, and AWS CodePipeline. The pipeline automates the deployment of a web application, ensuring that code changes are automatically built, tested, and deployed to a highly available environment.
  - **Service Used**:


- **Project 8**:  Building Web Applications based on Amazon EKS
  - **Description**: In this project, I built a web application based on Amazon Elastic Kubernetes Service (EKS). The architecture included creating a development environment using AWS Cloud9, building container images with Docker, uploading those images to Amazon Elastic Container Registry (ECR), deploying EKS clusters and services, exploring Container Insights, and implementing auto-scaling for pods and clusters. 
  - **Service Used**: 


- **Project 9**:  Large-scale Data Processing with Step Functions
  - **Description**: In this project, I implemented a large-scale data processing workflow using AWS Step Functions to orchestrate various tasks in a serverless architecture. The workflow utilized Amazon S3 for data storage, IAM for managing permissions, CloudWatch for monitoring and logging, and AWS X-Ray for tracing requests. 
  - **Service Used**:

- **Project 10**:  Deploying a Complete Machine Learning Fraud Detection Solution Using Amazon SageMaker

  - **Description**: In this project, I deployed a complete machine learning fraud detection solution using Amazon SageMaker. The architecture leverages various AWS services to build, train, and deploy a robust model capable of detecting fraudulent transactions.
  - **Service Used**: 

- **Project 11**:  Serverless Data Processing on AWS
  - **Description**: In this project, I implemented a serverless data processing solution using AWS services, including Amazon Kinesis, AWS Lambda, Amazon S3, Amazon DynamoDB, Amazon Cognito, and Amazon Athena. The architecture is designed to handle real-time data streams, process and store data efficiently, and enable ad-hoc querying for insights.
  - **Service Used**: 

- **Project 12**:  AWS Cloud Resume Challenge

  - **Description**: AWS Cloud Resume Challenge was is incredible learning experience and a taste of what real-world cloud architecture looks like. This project, inspired by @ForrestBrazeal  challenge, covers end-to-end deployment of a personal resume website using AWS services, combining serverless computing, infrastructure as code, CI/CD, and front-end development in a practical application.

  - **Service Used**: 

- **Project 13**:  Build an Automated Video Monitoring System with AWS IoT and AI/ML

  - **Description**: This project involved creating a real-time automated video monitoring system using AWS IoT and AI/ML services. By integrating AWS IoT Core for device communication and Amazon Rekognition for video analytics, I developed a solution that detects objects, faces, and events in video feeds. The system was further automated using AWS Lambda and CloudWatch to trigger responses based on the detected events, showcasing how IoT and AI/ML can streamline video surveillance processes for increased efficiency and security.

  - **Service Used**: 
