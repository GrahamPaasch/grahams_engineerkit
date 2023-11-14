# Infrastructure

![Hard](https://img.shields.io/badge/Difficulty-◆%20Hard-grey?style=flat-square&labelColor=000)
<a href="https://discord.gg/bDVYvG3Czd">![Need help?](https://img.shields.io/badge/Need%20help%3F%20-blue.svg?style=flat-square&logo=discord&logoWidth=15&labelColor=000&color=4d51cc)</a>

### With this module, you'll learn how to use cloud providers to orchestrate computing resources and create a scalable and resilient platform for your product.

<img width="1440" alt="Top-down view of shipping containers" src="https://user-images.githubusercontent.com/894178/138357403-29c2f0ab-0ade-4f72-ab1e-6a29932f8eba.png">

## Topics

### Cloud Providers

   With this topic, you'll learn about cloud computing and the wide range of services an application can use with this topic.
   
   #### Learning Outcomes
   * NOT DONE: Describe Infrastructure as a Service (IaaS)
   * NOT DONE: Describe Platform as a Service (PaaS)
   * NOT DONE: Describe Software as a Service (SaaS)
   * NOT DONE: List some typical cloud providers
   * NOT DONE: List some commonly used services from cloud providers
   * NOT DONE: Compare using cloud computing with on-premise computing

   #### Resources
   * NOT DONE: [A Cloud Guru `Resource`](https://acloudguru.com/)
   * NOT DONE: [AWS `Tool`](https://aws.amazon.com/)
   * NOT DONE: [Azure `Tool`](https://azure.microsoft.com/en-us/)
   * NOT DONE: [DigitalOcean `Tool`](https://www.digitalocean.com/)
   * NOT DONE: [Google Cloud Platform `Tool`](https://cloud.google.com/)
   * DONE: [Kubernetes Explained in 100 Seconds `Video`](https://www.youtube.com/watch?v=PziYflu8cB8)
   * NOT DONE: [Kubernetes starter kit `Tutorial`](https://github.com/digitalocean/Kubernetes-Starter-Kit-Developers)
   * DONE: [Top 50+ AWS Services Explained in 10 Minutes `Video`](https://www.youtube.com/watch?v=JIbIYCM48to)
   * DONE: [What is Kubernetes? `Video Series`](https://www.youtube.com/watch?v=cC46cg5FFAM&list=PLIivdWyY5sqLmnGdKSdQIXq2sd_1bWSnx)

   #### Exercises
   * NOT DONE: [Virtual Machine Provisioning](../exercises/infrastructure/virtual-machine-provisioning.md)
   
   ### Completion Notes
   * **A Cloud Guru:** 
   * **AWS:** 
   * **Azure:** 
   * **DigitalOcean:** 
   * **Google Cloud Platform:** 
   * **Kubernetes Videos/Tutorials:** 

Video Summary: Top 50+ AWS Services Explained in 10 Minutes
In this video, the presenter provides an overview of more than 50 Amazon Web Services (AWS) products and services, highlighting key features and use cases. AWS, launched in 2006 with just three products, has since expanded to offer a vast array of services catering to the needs of developers worldwide. The video takes you on a journey through various "aisles" of AWS services, summarizing their functionalities and applications.

Introduction
AWS was launched in 2006 with only three products: storage buckets, compute instances, and a messaging queue.
Today, AWS offers over 200 services, and many of them seem to overlap in functionality.
The video aims to provide an understanding of over 50 different AWS products.

Robotics and IoT
RoboMaker: Used for simulating and testing robots at scale.
IoT Core: Collects data from IoT devices, updates their software, and manages them remotely.
Ground Station: Connects data from satellites orbiting Earth through a global network of antennas.

Computing Services
Elastic Compute Cloud (EC2): Allows you to create virtual computers in the cloud with customizable specifications.
Elastic Load Balancing: Distributes traffic to multiple EC2 instances automatically.
CloudWatch: Collects logs and metrics from EC2 instances.
Auto Scaling: Creates new instances based on defined policies.
Elastic Beanstalk: Simplifies the deployment of web applications.
Lightsail: Offers an even simpler option for deploying websites.
Lambda: Introduces serverless computing, allowing you to run code in response to events.
Outposts: Enables running AWS APIs on your own infrastructure.
Snow Devices: Mini data centers that work in hostile environments.

Containerization
Elastic Container Registry (ECR): Stores and manages Docker container images.
Elastic Container Service (ECS): Allocates virtual machines for running containers.
EKS: Manages Kubernetes clusters.
Fargate: Allows containers to behave like serverless functions.
App Runner: A new 2021 product for easy container deployment.

Storage Services
Simple Storage Service (S3): The first AWS product, for storing files and objects.
Glacier: Archives files with higher latency but lower cost.
Elastic Block Storage (EBS): Ideal for applications with data processing needs.
Elastic File System (EFS): Provides fully managed file storage.
Database Options: A wide range of database products including SimpleDB, DynamoDB, DocumentDB, RDS, Aurora, Neptune, TimeStream, and Quantum Ledger Database (QLDB).

Analytics
Redshift: A data warehouse for structured data.
Lake Formation: Creates data lakes for unstructured data.
Kinesis: Captures real-time data streams.
Elastic MapReduce (EMR): A framework for processing massive datasets.
Glue: A serverless tool for extracting, transforming, and loading data.

Machine Learning
SageMaker: Facilitates machine learning model development and deployment.
Data Exchange: Allows purchase and subscription to third-party data.
Recognition: Recognizes objects and images.
Lex: Powers conversational bots.
DeepRacer: An actual race car for machine learning enthusiasts.

Essential Tools
Identity and Access Management (IAM): Provides access control.
Cognito: Manages user authentication and sessions.
Simple Notification Service (SNS): Sends push notifications.
Simple Email Service (SES): Sends emails.
CloudFormation: Creates templates for provisioning services.
Amplify: Provides SDKs for connecting to AWS infrastructure.
Cost Management: AWS Cost Explorer and Budgets for cost monitoring.

The video offers a comprehensive overview of AWS services, making it easier for developers to choose the right services for their specific needs.

   * **Virtual Machine Provisioning Exercise:**

----

### Infrastructure as Code

   With this topic, you'll learn how to provision cloud services quickly and reliably using infrastructure as code techniques.
   
   #### Learning Outcomes
   * Describe Infrastructure as Code
   * Use Terraform to provision infrastructure with a cloud provider
   * Explain some of the benefits of infrastructure as code compared to manually provisioning infrastructure
   
   #### Resources
   * [AWS CloudFormation `Tool`](https://aws.amazon.com/cloudformation/)
   * [Infrastructure as Code with Terraform `Tutorial`](https://learn.hashicorp.com/tutorials/terraform/infrastructure-as-code?in=terraform/aws-get-started)
   * [Terraform `Tool`](https://www.terraform.io/)
   * [Terraform in 100 Seconds `Video`](https://www.youtube.com/watch?v=tomUWcQ0P3k)

   #### Exercises
   * [Terraform the Cloud](../exercises/infrastructure/terraform-the-cloud.md)

----

### Backing Services

   With this topic, you'll learn how to work with the attached services required for an application to run.
   
   #### Learning Outcomes
   * Describe a backing service
   * Explain how you might create resilient backing services
   * Theorize how you might monitor backing services to ensure they are up
   
   #### Resources
   * [12 Factor App: Backing Services `Resource`](https://12factor.net/backing-services)

   #### Exercises
   * [Mapping Backing Services](../exercises/infrastructure/mapping-backing-services.md)
   * Setup Sentry.io and integrate it into your umbrella project (will your app go down if Sentry goes down?)
   * Setup a PostgreSQL database and integrate it into your umbrella project (will your app go down if the database goes down?)

----

### Managing Multiple Environments

   With this topic, you'll learn how to manage multiple environments such as dev, staging, and production for an application.
   
   #### Learning Outcomes
   * Describe what an environment is
   * Explain the purpose of development, staging, and production environments
   
   #### Resources
   * [Terraform Workspaces `Tool`](https://www.terraform.io/docs/cloud/workspaces/)
   * [12 Factor App: Dev/Prod Parity `Resource`](https://12factor.net/dev-prod-parity)

   #### Exercises
   * [Cloud Environment Replication](../exercises/infrastructure/cloud-environment-replication.md)

----

### Working with Cloud Engineers

   With this topic, you'll learn about the role of a cloud engineer and how to work with them on your team effectively.
   
   #### Learning Outcomes
   * Describe the role of a cloud engineer
   * Identify what you need from a cloud engineer to complete software engineering tasks
   * Explain how you might collaborate with a cloud engineer to design and provision infrastructure for an application

   #### Resources
   * [What is a Cloud Engineer? `Video`](https://www.youtube.com/watch?v=NBHc6tatwvo)
   * [The Phoenix Project: A Novel about IT, DevOps, and Helping Your Business Win `Book ($)`](https://www.amazon.com/Phoenix-Project-DevOps-Helping-Business/dp/0988262592)
   * [The Unicorn Project: A Novel about Developers, Digital Disruption, and Thriving in the Age of Data `Book ($)`](https://www.amazon.com/Unicorn-Project-Developers-Disruption-Thriving-ebook/dp/B07QT9QR41)

   #### Exercises
   * [Infrastructure Inventory](../exercises/infrastructure/infrastructure-inventory.md)
   * Pair with a Cloud Engineer on your team and solve an infrastructure problem with them!
