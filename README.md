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
  - **Objectives**: 
    * Create a cost budget to monitor spending
  - **Service Used**: 

- **Project 3**: Launch a Hello World Website on the Internet
  - **Description**: Deploy a simple "Hello World" website on an AWS EC2 instance to understand the process of launching and configuring an EC2 instance and making a basic web application available on the Internet.
   - **Objectives**: 
    * Launch a linux based EC2 instance in any one region of your choice in a public subnet
    * Setup a security group that allows http/https connections from the Internet, and ssh from your IP address
    * Ssh into the EC2 instance
    * Setup a webserver on the EC2 instance
    * Add a simple hello world header to the index.html file
    * Hit the public IP address from a browser and confirm the site is served
  - **Service Used**: 

- **Project 4**: Push a Docker Image to Amazon ECR Repository
  - **Description**: Build a Docker image and push it to an Amazon ECR repository. This includes creating the repository, tagging the image, and using AWS CLI to authenticate and upload the image.
  - **Objectives**:
    * Create your Amazon ECR repository
    * Authenticate your Docker to Amazon ECR
    * Tag your Docker image with the Amazon ECR repository
    * Push your image to Amazon ECR
  - **Service Used**: 

- **Project 5**:  Creating an Amazon RDS DB Instance 
  - **Description**: Set up and configure a database instance using Amazon RDS. This includes choosing the appropriate instance type, configuring security settings, setting up backups and maintenance windows, and ensuring high availability.
  - **Objectives**:
    * Setup a database instance on Amazon RDS
    * Create any database instance on RDS
    * Connect to RDS database instance from your local
  - **Service Used**: 

- **Project 6**:  Create a DynamoDB Table
  - **Description**: This project involves creating a DynamoDB table with provisioned capacity. Three random items to be inserted into the table. A scan operation was performed to retrieve all items, and a query operation to be used to fetch a single item based on specific criteria.
  - **Objectives**: 
    * Create a DynamoDB table with provisioned capacity
    * Create three random items in the table
    * Run a scan on the table that returns all three items
    * Run a query on the table that returns a single item
  - **Service Used**: 

- **Project 7**:  Create an S3 Bucket and store an object in it
  - **Description**: This project involves creating an Amazon S3 bucket using the AWS Management Console and uploading a file into the bucket. Amazon S3 (Simple Storage Service) is used to store and retrieve any amount of data at any time, and this project demonstrates the basic steps of setting up and using S3 for storage.
  - **Objectives**:
    * Create S3 bucket
    * Upload an object (any file) into the bucket
  - **Service Used**: 

- **Project 8**:  Introduction to SNS (Simple Notification Service)
  - **Description**: This project involves creating an Amazon SNS (Simple Notification Service) topic, subscribing an email address to the topic, and confirming the subscription through the email. After confirming, a test message is sent through the SNS topic to verify that the email address receives the notification, demonstrating the basic functionality and setup of SNS for sending notifications.
  - **Objectives**:
    - Create an SNS topic
    - Subscribe to that SNS topic with an email address of yours
    - Make sure to accept the subscription in the email you receive
    - Send a test message through the SNS topic
    - Make sure you received the message to your email address
  - **Service Used**: 

- **Project 9**:  Create a Lambda Function to Add Two Numbers
  - **Description**: Developed an AWS Lambda function using Python that takes two numbers as input, adds them together, and returns the result. The function also print the result out in the logs.
  - **Objectives**:
    - Create an AWS Lambda with a language of your choice to add 2 numbers supplied as input and return the result.
    -  Print the result out in the logs.
  - **Service Used**: 

- **Project 10**:  Host a Simple Static Webpage with S3 and CloudFront
  - **Description**: Set up an S3 bucket to host a static webpage and uploaded the webpage content. Configured an Amazon CloudFront distribution to use the S3 bucket as its origin, ensuring that the webpage content is accessible only through the CloudFront endpoint to enhance security and performance.
  - **Objectives**:
    * Create an S3 bucket and upload a simple static webpage
    * Create a CloudFront distribution and use the S3 bucket as origin
    * Make sure that the bucket's content can be accessed only through the CloudFront endpoint
  - **Service Used**: 
    
 - **Project 11**:  Use a Managed Config Rule
    - **Description**: Implemented and monitored an AWS Config rule to ensure compliance with encryption policies for EBS volumes. Enabled AWS Config in the US-EAST-1 region, selected the managed Config rule `encrypted-volumes`, and launched an EC2 instance with an unencrypted EBS volume to verify that the Config rule detects non-compliance.
    - **Objectives**:
      - Turn on AWS Config in the US-EAST-1 region
      - Choose the managed Config rule eg. encrypted-volumes
      - Launch an EC2 instance without an encryped EBS volume
      - Monitor AWS Config until it detects there is an EBS volume that is unencrpyted
    - **Service Used**:
    
## Level 2 (Intermediate Projects)
These projects are intended for individuals with a basic AWS understanding who wish to explore more advanced scenarios.

- **Project 1**: Create an Auto Scaling Group
  - **Description**: Configured an Auto Scaling Group (ASG) with a launch configuration that automatically scales between 2 and 5 EC2 instances. Monitored the ASG’s behavior by manually terminating an instance and observing how the ASG maintains the desired capacity. Also, adjusted the desired number of instances and explored scaling policies based on CloudWatch metrics.
  - **Objectives**:
    - Create a Launch Configuration
    - Create an Auto Scaling Group with a minimum of two and maximum of five EC2 instances
    - Terminate one instance manually
    - After the ASG is in place, increase the desired number of instances to three
    - Delete all the resources you created
  - **Services Used**: 

- **Project 2**: Deploy a Docker Container Image on AWS Fargate
  - **Description**: Deployed a Docker container image on AWS Fargate by configuring a container with a Docker image, setting up a task definition, defining a service, and deploying it on an ECS cluster. Explored memory limits, task roles, load balancers, and security group configurations.
  - **Objectives**:
    - Configure your container with your Docker image
    - Configure your task definition
    - Define your service
    - Configure your cluster
  - **Services Used**: 

- **Project 3**: Create an Aurora RDS Database
  - **Description**: Created an Aurora RDS database with MySQL compatibility. Configured a security group to allow public access for testing purposes, set up the database using `db.r5.large` instance type, and connected to the instance using MySQL Workbench. Verified functionality by creating a test table, then deleted the database and ensured proper resource cleanup.
  - **Objectives**:
    - Create a Security Group in your default VPC that allows traffic from `0.0.0.0/0` (public internet) on port `3306`
    - Use the "standard create" mode and choose "MySQL compatibility" with "regional" and "Dev/Test" mode
    - Specify your own password for the database
    - Choose the db.r5.large instance size
    - Choose the region's default VPC
    - Enable "Public Access" and add the above created Security Group
    - Create the database
    - Connect from your computer to the newly created database with a MySQL DBMS like [MySQL Workbench](https://dev.mysql.com/downloads/workbench/?os=src) or [Sequel Ace](https://github.com/Sequel-Ace/Sequel-Ace)
    - Create a test table in your database to verify everything is working correctly
    - Delete the database
  - **Services Used**: 
 
- **Project 4**: Setup a Simple State Machine with at least 2 Steps
  - **Description**: Create a simple AWS Step Functions state machine consisting of two AWS Lambda functions. Build on past services deployed to make a production level example
  - **Objectives**:
    * Create an AWS Lambda to add 2 numbers supplied as input
    * Create an AWS Lambda to return the square of a number
    * Create a state machine to connect the above two Lambdas
    * Execute the state machine and verify the output.
  - **Services Used**: 
 
- **Project 5**: Create a Serverless API  
  - **Description**: Developed a serverless API using AWS Lambda and API Gateway. The Lambda function responds with the message 'Hello Serverless World!'. An API Gateway was created to expose the Lambda function as an HTTP endpoint, and the API was secured using an API Key. The API endpoint was successfully tested using POSTMAN to verify both functionality and security.
  - **Objectives**: 
    - Create an AWS Lambda with a language of your choice, the purpose of this Lambda is to respond with a 'Hello Serverless World!' message.
    - Create an API Gateway endpoint and connect it to the AWS Lambda function created above and deploy it as an API that can be consumed from POSTMAN.
    - Secure the API with an API Key  
  - **Services Used**: 
 
- **Project 6**: Create a CloudWatch Alarm  
    - **Description**: Configured a CloudWatch Alarm to monitor EC2 NetworkIn traffic. An EC2 instance was launched with a simple Apache web server installed via UserData. The CloudWatch Alarm was set up to monitor the **NetworkIn** metric, with a 5-minute evaluation period and a low static threshold of 5000 bytes. The alarm was triggered by generating traffic to the instance, ensuring the monitoring setup was functional and reliable.
    - **Objectives**:
      - Launch an EC2 t2.micro instance with a public IP address and supply the [provided bash script](OPS04-AWS200-userdata.sh) to install a simple website with an apache server in the UserData.
      - Visit the the public IP so that you are generating NetworkIn. You need to do this so the Metric appears selectable when create your CloudWatch Alarm
      - Create a CloudWatch Alarm and use EC2 NetworkIn as the metric
      - Set your CloudWatch Alarm to use a 5 minute period
      - Set your CloudWatch Alarm to a very low static threshold such as 5000
      - Set the Datapoint to alarms to 3 of 4
      - Try to get the Alarm to trigger an Alert state by visiting the website and generating NetworkIN
    - **Services Used**: 
 
- **Project 7**: Create a new CMK in KMS and encrypt an object
  - **Description**: Created a **Customer Master Key (CMK)** using AWS Key Management Service (KMS) to ensure secure encryption of an object uploaded to an S3 bucket. The object was encrypted using the custom CMK, enhancing data security and encryption at rest. Key management and access control were configured for this setup, ensuring only authorized users could interact with the encrypted object.
  - **Objectives**:
    - Create a new Customer Master Key (CMK) in Key Management Service (KMS)
    - Create a new S3 bucket
    - Upload an object (file) to the S3 Bucket
    - Encrypt the uploaded file with your custom CMK
  - **Services Used**: 

- **Project 8**:  Create an EFS Shared File System
  - **Description**: Set up an Amazon Elastic File System (EFS) to provide a shared file system across multiple Amazon EC2 instances in separate Availability Zones within the same region.
  - **Objectives**:
    - Create an EFS file system
    - Spin up two EC2 instances in two seperate AZs in the same region
    - Make sure you can SSH into both instances
    - Mount the EFS volume on both instances
    - Create a simple text file on the EFS volume with Instance-1
    - Open that file on the EFS volume with Instance-2
  - **Service Used**: 


## Level 3 (Expert Projects)
These projects are the most challenging, demonstrating advanced AWS solutions and best practices.

- **Project 1**:  SQLServer Native Backup and Restore on RDS
  - **Description**: Implemented SQL Server backup and restore on AWS RDS involving Amazon S3 bucket.
  - **Objectives**:
    - Enable native backup and restore on RDS
    - Take native SQL Server backup to S3 bucket 
    - Restore native backup from S3 bucket
  - **Service Used**: 

- **Project 2**:  Create a Cluster of Virtual Machines Using Docker Swarm
  - **Description**: Set up a Docker Swarm cluster across five EC2 instances, with one manager node and four worker nodes, and tested it by deploying an Nginx service.
  - **Objectives**:
  - **Service Used**: 

- **Project 3**:  Build a Basic Web Application
  - **Description**: This project involves building a full-stack web application using AWS Amplify. It features a simple React frontend with user authentication, a serverless function to handle user sign-ups, and a DynamoDB database for storing user emails. The application leverages AWS’s robust and scalable cloud services to deliver a seamless user experience, allowing users to sign up, log in, and store information securely.
  - **Objectives**:
  - **Service Used**: 

 - **Project 4**:  Build a Serverless Recipe Generator with AWS Amplify and Amazon Bedrock
   - **Description**: In this project, I built a serverless web application using AWS Amplify, integrated with Amazon Bedrock and the Claude 3 Sonnet foundation model for Generative AI. The application allows users to enter a list of ingredients, and in return, it generates creative and delicious recipes powered by AI. The front end is hosted on AWS Amplify, offering continuous deployment, while the backend handles requests to generate recipes from a list of ingredients. AWS services like Cognito for authentication, AppSync for API management, and Lambda for serverless functions are used to power the app.
    - **Objectives**:
    - **Service Used**: 

- **Project 5**:  Building with Generative AI on AWS using PartyRock, Amazon Bedrock, and Amazon Q
    - **Description**: In this project, I worked on three independent projects using Amazon Bedrock and PartyRock:
      -  Using PartyRock, I quickly built a book recommendation app that generates personalized suggestions based on the user’s mood and allows for an interactive chatbot experience. This no-code tool made it easy to create and deploy a simple app without writing a single line of code.
      -  In Amazon Bedrock, I experimented with powerful foundation models like Claude 3 Sonnet for chat, Amazon Titan for text generation, and Titan Image Generator for creating images from text prompts. This step showed me how to integrate AI models for more creative and dynamic use cases in real-world applications.
      -  Lastly, I implemented a document-based AI model that retrieves and uses context to answer questions. I set up embeddings using Amazon Titan, performed similarity searches with FAISS, and used the Claude 3 Sonnet model to generate accurate, context-based responses to user queries. This showcased how to build applications that not only generate content but also pull in relevant information from external sources.
    - **Objectives**:
    - **Service Used**: 

- **Project 6**:  Multi-Tier, Highly Available, Fault-Tolerant Web Application
  - **Description**: In this project, I designed and implemented a multi-tier, highly available, and fault-tolerant web application using various AWS services including Amazon VPC, Amazon EC2, Amazon Aurora, and Amazon S3. This architecture ensures scalability, resilience, and efficient resource management. This experience is part of my journey to becoming a Cloud Engineer, focusing on building robust cloud-based applications.
  - **Objectives**:
  - **Service Used**:

- **Project 7**:  Building a Highly Available WordPress Web Application
  - **Description**: In this project, I designed and implemented a highly available WordPress web application on AWS using various services, including Amazon VPC, Amazon RDS, Amazon EFS, and Amazon EC2 with Auto Scaling and Application Load Balancer (ALB). This architecture ensures scalability, resilience, and efficient resource management.
  - **Objectives**:
  - **Service Used**:

- **Project 8**:  Create a Continuous Delivery Pipeline
  - **Description**: In this project, I created a continuous delivery pipeline using AWS services, including AWS Elastic Beanstalk, AWS CodeBuild, and AWS CodePipeline. The pipeline automates the deployment of a web application, ensuring that code changes are automatically built, tested, and deployed to a highly available environment.
  - **Objectives**:
  - **Service Used**:


- **Project 9**:  Building Web Applications based on Amazon EKS
  - **Description**: In this project, I built a web application based on Amazon Elastic Kubernetes Service (EKS). The architecture included creating a development environment using AWS Cloud9, building container images with Docker, uploading those images to Amazon Elastic Container Registry (ECR), deploying EKS clusters and services, exploring Container Insights, and implementing auto-scaling for pods and clusters. 
  - **Objectives**:
  - **Service Used**: 


- **Project 10**:  Large-scale Data Processing with Step Functions
  - **Description**: In this project, I implemented a large-scale data processing workflow using AWS Step Functions to orchestrate various tasks in a serverless architecture. The workflow utilized Amazon S3 for data storage, IAM for managing permissions, CloudWatch for monitoring and logging, and AWS X-Ray for tracing requests. 
  - **Objectives**:
  - **Service Used**:

- **Project 11**:  Deploying a Complete Machine Learning Fraud Detection Solution Using Amazon SageMaker
  - **Description**: In this project, I deployed a complete machine learning fraud detection solution using Amazon SageMaker. The architecture leverages various AWS services to build, train, and deploy a robust model capable of detecting fraudulent transactions.
  - **Objectives**:
  - **Service Used**: 

- **Project 12**:  Serverless Data Processing on AWS
  - **Description**: In this project, I implemented a serverless data processing solution using AWS services, including Amazon Kinesis, AWS Lambda, Amazon S3, Amazon DynamoDB, Amazon Cognito, and Amazon Athena. The architecture is designed to handle real-time data streams, process and store data efficiently, and enable ad-hoc querying for insights.
  - **Objectives**:
  - **Service Used**: 


- **Project 13**:  Build an Automated Video Monitoring System with AWS IoT and AI/ML
  - **Description**: This project involved creating a real-time automated video monitoring system using AWS IoT and AI/ML services. By integrating AWS IoT Core for device communication and Amazon Rekognition for video analytics, I developed a solution that detects objects, faces, and events in video feeds. The system was further automated using AWS Lambda and CloudWatch to trigger responses based on the detected events, showcasing how IoT and AI/ML can streamline video surveillance processes for increased efficiency and security.
  - **Objectives**:
  - **Service Used**: 

- **Project 14**:  AWS Cloud Resume Challenge
  - **Description**: [ AWS Cloud Resume Challenge ](https://cloudresumechallenge.dev/docs/the-challenge/aws/) was is incredible learning experience and a taste of what real-world cloud architecture looks like. This project, inspired by @ForrestBrazeal  challenge, covers end-to-end deployment of a personal resume website using AWS services, combining serverless computing, infrastructure as code, CI/CD, and front-end development in a practical application.
  - **Objectives**:
  - **Service Used**: 
