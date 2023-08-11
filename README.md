# Extensive list and short descriptions of AWS services

While preparing for AWS Cloud Practitioner certification I found constant references to AWS services that have not being discussed before, so I thouhght that having an extensive list of AWS services would be useful.

The list is far from complete, pull requests and comments very much welcome. Please keep the list descriptions concise and relevant for general knowledge.

# Service areas:
## Compute
   * Amazon EC2 (Elastic Compute Cloud)
      * Virtual Servers in the cloud
         * Auto Scaling (instances)
         * EC2 Spot Instances
            * Up to 90% off
            * Auto Scaling (Spot fleets)
   * Amazon Lightsail
      * Launch and manage virtual private servers
   * AWS App Runner
      * Easy containerized production web applications at scale
   * AWS Batch
      * Easily run batch and ML compute jobs 
   * AWS Compute Optimizer
      * ML powered analysis of resources configuration and utilisation
   * AWS Elastic Beanstalk
      * Easy web app deployment and scaling
   * AWS Fargate
      * Serverless compute for containers
   * AWS Lambda
      * Serverless code
   * AWS Local Zones
      * Run latency sensitive applications closer to end users extending your VPC to the local zone
   * AWS Outposts
      * Run AWS infrastructure and services on premises for a consistent hybrid experience
   * AWS Serverless Application Repository
      * Discover, deploy, and publish serverless applications
   * AWS SimSpace Weaver
      * Build dynamic, large-scale spatial simulations on AWS managed infrastructure
   * AWS Wavelength
      * Deliver ultra-low-latency applications for 5G devices
   * VMware Cloud on AWS
      * Fully supported, ready-to-run service from the creators of the software, VMware
## Containers
   * Amazon ECR (Elastic Container Registry)
      * Fully managed container registry
   * Amazon ECS (Elastic Container Service)
      * Run containers
         * Auto Scaling (tasks)
   * Amazon EKS (Elastic Kubernetes Service)
      * Run Kubernetes
   * AWS App2Container
      * Containerize and migrate existing applications
   * AWS Copilot
      * CLI for containerized apps
   * AWS Fargate
      * Serverless compute for containers (ECS and EKS)
   * Red Hat OpenShift Service on AWS
      * Managed Red Hat container platform on  AWS
## Storage
   * Amazon EBS (Elastic Block Storage)
      * Block devices ) file systems, databases, apps, etc.
         * Single Availability Zone
   * Amazon EFS (Elastic File System)
      * Serverless elastic storage
         * NFS 4.0 and 4.1
   * Amazon FSx
      * Easy launch, run and scale file systems
         * NEtApp ONTAP. OpenZFS, Windows File Server, Lustre
   * Amazon S3 (Simple Storage Service)
      * Object Storage for any use
         * Storage tiers for infrequent access and archival data
         * Automatic multi-region replication
   * Amazon S3 Glacier
      * Long term storage
   * AWS Backup
      * Centrally manage and automate data protection across aws services and on premises
   * AWS Snow Family
      * Encrypted data transfer devices
         * Snowcone - 8TB HDD or 14TB SSD
         * Snowball Edge Storage Optimised 80TB HDD and 210TB SSD
         * Snowball Edge Compute Optimised 28TB SSD
         * Snowmobile 100PB 45ft. Shipping container
   * AWS Storage Gateway
      * Provide on-premises applications with access to virtually unlimited cloud storage
   * AWS DRS (Elastic Disaster Recovery)
      * Scalable, cost-effective, fast, reliable application recovery of on-premises and cloud-based applications
         * Point-in-time recovery
## Databases
   * Amazon Aurora
      * Fully managed MySQL and PostgreSQL compatible relational database
         * Auto Scaling (replicas)
   * Amazon DocumentDB
      * Fully managed JSON document DB with mongoDB compatibility
   * Amazon DynamoDB
      * Fully managed NoSQL database
         * Auto Scaling (tables and indexes)
   * Amazon ElastiCache
      * Fully managed, Redis- and Memcached-compatible service
   * Amazon Keyspaces (for Apache Cassandra)
      * Cassandra-compatible managed DB service (NoSQL Wide-column store)
   * Amazon MemoryDB for Redis
      * Redis-compatible durable in-memory database
   * Amazon Neptune
      * Fully managed graph database
   * Amazon RDS (Relational Database Server)
      * Managed DB service for MySQL, MariaDB, PostgreSQL, Oracle, SQL Server, Amazon Aurora (MySQL and PostgreSQL)
         * Can be deployed on-premises with Amazon RDS on AWS Outposts
   * Amazon Redshift
      * Analyse structured and semi-structured data across warehouses, operational DBs and data lakes using SQL
   * Amazon Timestream
      *  Fast, scalable, and serverless time-series database service
## Networking and Content Delivery
   * Amazon API Gateway
      * Fully managed service for developers to create, publish, maintain, monitor, and secure APIs at any scale
         * RESTful APIs
         * Websocket APIs
   * Amazon CloudFront
      * CDN service built for high performance, security, and developer convenience
      * 450+ globally dispersed Points of Presence
      * 1TB data transfer out on Free Tier
   * Amazon Route 53
      * Highly available and scalable Domain Name System (DNS) web service
   * Amazon VPC
      * Virtual Private Cloud,  logically isolated section of Amazon Web Services Cloud
      * Public and private subnets, each on a single AZ
      * Assignable IPv4 and IPv6 addresses to VPC and subnets, bring public addresses
      * Route tables for subnets or gateways
      * Internet gateway, gateway to other networks, AWS service endpoints or AWS PrivateLink
      * VPC Peering connections route traffic between two VPCs
      * Traffic Mirroring for deep packet inspection
      * Transit gateways as central hubs for traffic between VPCs, VPN connections and AWS Direct Connect connections
      * VPC Flow Log captures traffic information
      * VPN connections from on-premises network
   * AWS App Mesh
      * Application-level networking for all services
   * AWS Cloud Map
      * Service discovery for cloud resources
      * Register resources with custom names, Cloud Map checks the resources health and location
   * AWS Direct Connect
      * Connect your on-premises infrastructure and an AWS location through a dedicated or partner hosted connection
   * AWS Global Accelerator
      * Provide two global static IPs as entry point to your resources
   * AWS Private 5G
      * Managed service for easy deployment, operation and scaling of your private mobile network
      * Hardware and software provided by AWS
   * AWS PrivateLink
      * Private connectivity between your VPC and supported AWS services
      * Doesn’t expose your traffic to the public internet
   * AWS Transit Gateway
      * Connect VPCs, accounts and on-premises networks to a single gateway
   * AWS Verified Access (Preview)
      * Secure access to corporate apps without a VPN connection
      * Built on Zero Trust principles, validates every app request
   * AWS VPN
      * Connect on-premises networks and remote workers to the cloud
   * ELB (Elastic Load Balancing)
      * Distribute network traffic
      * Application, Gateway and Network Load balancers
      * Application LB targets EC2 (autoscaling too), Lambda, Fargate, EKS, ECS, IP addresses
      * Network LB targets the same plus application LB
      * 750 hours free per month on free tier
## Security, Identity and Compliance
   * Amazon Cognito
      * Implement secure frictionless scalable customer identity and access management for web and mobile apps with a hosted UI with your branding
      * Use social or enterprise identity providers
      * 50000 active users free per month
   * Amazon Detective
      * Using ML, simplifies the investigative process and helps security teams conduct faster and more effective investigations
   * Amazon GuardDuty
      * Continuous monitoring and Intelligent threat detection for your AWS account and services
   * Amazon Inspector
      * Automated and continuous vulnerability management at scale for EC2, lambda and ECS. Discovers  and scans workloads
   * Amazon Macie
      * Use ML and pattern matching based to discover and protect sensitive data on S3
      * Use Macies list of data types or create your own
   * Amazon Security Lake (Preview)
      * Centralise security data from AWS, SaaS, on premises and cloud sources
      * Adopted the OCSF (Open Cybersecurity Schema Framework)
   * Amazon Verified Permissions (Preview)
      * provides customer applications with the ability to control which users can perform which actions
   * AWS Artifact
      * Access compliance-related infromation
   * AWS Audit Manager
      * Continually audit your AWS usage to simplify risk and compliance assessment
   * AWS Certificate Manager
      * Provision and manage SSL/TLS certificates with AWS services and connected resources
   * AWS CloudHSM
      * Generate and use keys on dedicated hardware security module instances
   * AWS Directory Service
      * Fully managed Microsoft Active Directory service
   * AWS Firewall Manager
      * Centrally configure and manage firewall rules across your accounts
   * AWS IAM Identity Center (Successor to AWS Single Sign-On)
      * Centrally manage workforce access to multiple AWS accounts and applications
   * AWS Identity and Access Management
      * Specify who or what can access services and resources in AWS, centrally manage fine-grained permissions, and analyse access to refine permissions across AWS.
      * Users, Groups, Roles, Policies
   * AWS KMS (Key Management Service)
      * Create and control keys used to encrypt or digitally sign your data
   * AWS Network Firewall
      * Define firewall rules that provide fine-grained control over network traffic
   * AWS Resource Access Manager
      * Securely share your resources across AWS accounts
   * AWS Secrets Manager
      * Manage, retrieve, and rotate database credentials, application credentials, OAuth tokens, API keys, and other secrets throughout their lifecycles
   * AWS Security Hub
      * Get a comprehensive view of your security state in AWS
      * Check your environment against security industry standards and best practices
   * AWS Shield
      * Managed DDoS protection
   * AWS WAF
      * Protects against common exploits such as SQL Injection and XSS (cross-site scripting)
## Analytics
   * Amazon Athena
      * Analyze petabyte-scale data where it lives with ease and flexibility
   * Amazon CloudSearch
      * Fully managed service for website or application search solution
   * Amazon DataZone (Preview)
      * Discover and share data at scale across organizational boundaries with governance and access control
   * Amazon EMR (Elastic Map Reduce)
      * Cloud big data solution for petabyte-scale data processing, interactive analytics, and machine learning
      * Use open-source frameworks such as Apache Spark, Apache Hive, and Presto
   * Amazon FinSpace
      * Data processing and analytics for Capital Markets with Managed kdb Insights
   * Amazon Kinesis
      * Cost-effectively processes and analyzes streaming data at any scale as a fully managed service
   * Amazon MSK (Managed Streaming for Apache Kafka)
      * Ingest and process streaming data in real time with fully managed Apache Kafka
   * Amazon OpenSearch Service
      * Open source, distributed search and analytics suite derived from Elasticsearch
      * Real-time search, monitoring, and analysis of business and operational data
      * Up to 750 hours per month on t2 ant t3 small.search instances with Free Tier
   * Amazon QuickSight
      * unified business intelligence (BI) at hyperscale
   * Amazon Redshift
      * Analyse structured and semi-structured data across warehouses, operational DBs and data lakes using SQL
   * AWS Clean Rooms (Preview)        
      * Analyze and collaborate on collective datasets without sharing or copying one another's underlying data
      * Create a secure data clean room in minutes, and collaborate with any other company on the AWS Cloud to generate unique insights
   * AWS Data Exchange
      * Vast portfolio of third-party data sets
   * AWS Data Pipeline
      *  Process and move data between different AWS compute and storage services, as well as on-premises data sources, at specified intervals
   * AWS Glue
      * Simple, scalable serverless data integration
      * Discover, prepare, move, and integrate data from multiple sources for analytics, machine learning (ML), and application development
      * 1 million objects stored free
   * AWS Lake Formation
      * Build a secure data lake in days
      * Making data available for wide-ranging analytics
## Cost Management
   * AWS Cost Explorer
      * Tool that enables you to view and analyze your costs and usage
      * AWS Cost Explorer API
      * Rightsizing Recommendations
         * Helps you identify cost-saving opportunities by downsizing or terminating instances in EC2
      * Reserved Instance recommendations
         * Enable Cost Explorer to get Amazon EC2, Amazon RDS, ElastiCache, OpenSearch Service, and Amazon Redshift Reserved Instance (RI) 
   * AWS Cost and Usage Reports
      * The most comprehensive set of cost and usage data available published to a S3 bucket
   * AWS Consolidated Billing
      * Consolidate billing and payment for multiple AWS accounts
      * Combine the usage across all accounts in the organization to share the volume pricing discounts, Reserved Instance discounts, and Savings Plans
   * AWS Purchase Order Management
      * Use your Billing and Cost Management console to manage your purchase orders and configure how they reflect on your invoices
   * AWS Credits
      *  Redeem Your AWS Promotional Credit
   * AWS Cost Anomaly Detection
      * Use machine learning models to detect and alert on anomalous spend patterns in your deployed AWS services
   * AWS Budgets
      * Track and take action on your AWS costs and usage
   * AWS Budget Actions
      * Use AWS Budgets to run an action on your behalf when a budget exceeds a certain cost or usage threshold
   * Savings Plans
      * Reduce your bill by committing to a consistent amount of compute usage (measured in $/hour)
      * Save up to 72 percent on your AWS compute workloads
   * AWS Reserved Instances
      * Provide up to 72% discount and provide a capacity reservation when used in a specific Availability Zone
   * AWS Free Tier
      * Free Trials
      * 12 months free
      * Always free
      * Available for more than 100 products
## Management and Governance
   * Amazon CloudWatch
      * Observe and monitor resources and applications on AWS, on premises, and on other clouds
   * Amazon Managed Grafana
      * Fully managed service for grafana open source analytics platform
      * Query, visualize, and alert on your metrics, logs, and traces
   * Amazon Managed Service for Prometheus
      * provides alerts on containerized applications and infrastructure at scale
      * integrated with EKS, ECS, and AWS Distro for OpenTelemetry.
   * AWS Chatbot
      * Interactive agent that makes it easier to monitor and interact with your AWS resources in your Microsoft Teams and Slack channels
   * AWS CloudFormation
      * Infrastructure as code to model and setup AWS resources
      * Allows resource lifecycles to be managed repeatably, predictable, and safely, while allowing for automatic rollbacks, automated state management, and management of resources across accounts and regions
   * AWS CloudTrail
      * Track user activity and API usage
   * AWS CLI (Command Line Interface)
      * Unified tool to manage your AWS services
      * Allows use of scripts for AWS resource management
   * AWS Compute Optimizer
      * Analyzes the configuration and utilization metrics of your AWS resources
      * Generates optimization recommendations to reduce the cost and improve the performance of your workloads
   * AWS Config
      * Continually assesses, audits, and evaluates the configurations and relationships of your resources on AWS, on premises, and on other clouds
      * Evaluate resources, and enforce compliance
   * AWS Control Tower
      * Orchestrates multi-account AWS environment  with multiple AWS services on your behalf while maintaining the security and compliance needs of your organization
   * AWS Distro for OpenTelemetry
      * Auto-instrument trace sending from Java apps to AWS X-Ray
      * Analyze trace data and debug errors
   * AWS Launch Wizard
      * Size, configure, and deploy third party applications on AWS
   * AWS License Manager
      * Manage your software licenses from vendors, such as Microsoft, SAP, Oracle, and IBM, across AWS and your on-premises environments.
   * AWS Managed Services
      * Helps you adopt AWS at scale and operate more efficiently and securely
      * leverage standard AWS services and offer guidance and execution of operational best practices
      * Provides proactive, preventative, and detective capabilities that raise the operational bar and help reduce risk without constraining agility
   * AWS Management Console
      * Web-based user interface
   * AWS Management Console Mobile Application
      * View and manage a select set of resources and receive push notifications to stay informed and connected with your AWS resources while on-the-go
   * AWS OpsWorks
      * Configuration management service that provides managed instances of Chef and Puppet
      * Use code to automate the configurations of your servers
   * AWS Organizations
      *  Easily allocate resources, group accounts, and apply governance policies to accounts or groups.
   * AWS Health Dashboard
      * Learn about the availability and operations of AWS services
   * AWS Proton
      * Deployment workflow tool for modern applications
      * Help platform and DevOps engineers achieve organizational agility
   * AWS Resilience Hub
      * Central place to define, validate, and track the resilience of your applications on AWS
   * AWS Service Catalog
      * Centrally manage your cloud resources to achieve governance at scale of your infrastructure as code (IaC) templates
      * Written in CloudFormation or Terraform
      * 1000 Free API calls per month
   * AWS Service Management Connector
      * Streamlines cloud operations of AWS resources with your existing operational ITSM tooling
   * AWS Systems Manager
      * End-to-end management solution for resources on AWS and in multicloud and hybrid environments.
      * 13 AWS Systems Manager features free
   * AWS Trusted Advisor
      * Provides recommendations that help you follow AWS best practices
      * AWS Basic Support and AWS Developer Support customers can access core security checks and checks for service quotas
      *  AWS Business Support and AWS Enterprise Support customers can access all checks, including cost optimization, security, fault tolerance, performance, and service quotas
   * AWS Well-Architected Tool
      * Help you review the state of your applications and workloads against architectural best practices, identify opportunities for improvement, and track progress over time.
## Front-End Web & Mobile
   * Amazon API Gateway
      * Build, deploy and manage APIs
   * Amazon Location Service
      * Add location data to apps
   * Amazon Pinpoint
      * Multi channel marketing communications
   * Amazon SES (Simple Email Service)
      * High-scale inbound and outbound email
   * AWS Amplify
      * Build, deploy, host and manage scalable web and mobile apps
   * AWS AppSync
      * Fully-managed, scalable GraphQL APIs
   * AWS Device Farm
      * Test Android, iOS and web apps on real devices
## Developer Tools
   * Amazon CodeCatalyst (Preview)
   * Amazon CodeGuru
   * Amazon Corretto
   * AWS Cloud Control API
   * AWS CDK (Cloud Development Kit)
   * AWS Cloud9
   * AWS CloudShell
   * AWS CodeArtifact
   * AWS CodeBuild
   * AWS CodeCommit
      * Private GIT repositories
   * AWS CodeDeploy
   * AWS CodePipeline
   * AWS CodeStar
   * AWS (CLI) Command Line Interface
   * AWS Device Farm
      * Test Android, iOS and web apps on real devices
   * AWS Fault Injection Simulator
   * AWS Tools and SDKs
   * AWS X-Ray
      * App debug and analysis
   * Amazon CodeWhisperer
## Application Integration
   * Amazon AppFlow
   * Amazon EventBridge
   * Amazon (MWAA) Managed Workflows for Apache Airflow
   * Amazon MQ
   * Amazon (SNS) Simple Notification Service
   * Amazon SQS (Simple Queue Service)
   * AWS Step Functions
## Customer Engagement
## Internet of Things
   * AWS IoT Core
   * AWS IoT FleetWise
   * AWS IoT SiteWise
   * AWS IoT TwinMaker
   * AWS IoT Greengrass
   * AWS IoT 1-Click
   * AWS IoT Analytics
   * AWS IoT Button
   * AWS IoT Device Defender
   * AWS IoT Device Management
   * AWS IoT EduKit
   * AWS IoT Events
   * AWS IoT RoboRunner
   * AWS Partner Device Catalog
   * FreeRTOS
## Machine Learning
   * Amazon Augmented AI
   * Amazon Bedrock
   * Amazon CodeGuru
   * Amazon Comprehend
   * Amazon DevOps Guru
   * Amazon Elastic Inference
   * Amazon Forecast
   * Amazon Fraud Detector
   * Amazon HealthLake
   * Amazon Kendra
   * Amazon Lex
   * Amazon Lookout for Equipment
   * Amazon Lookout for Metrics
   * Amazon Lookout for Vision
   * Amazon Monitron
   * Amazon Omics
   * Amazon Personalize
   * Amazon Polly
   * Amazon Rekognition
   * Amazon SageMaker
   * Amazon SageMaker Ground Truth
   * Amazon Textract
   * Amazon Transcribe
   * Amazon Translate
   * Apache MXNet on AWS
   * AWS Deep Learning AMIs
   * AWS Deep Learning Containers
   * AWS DeepComposer
   * AWS DeepLens
   * AWS DeepRacer
   * AWS Inferentia
   * AWS Panorama
   * PyTorch on AWS
   * TensorFlow on AWS
   * Amazon CodeWhisperer 
## Robotics
   * AWS RoboMaker
## AR and VR
## Satellite
   * AWS Ground Station
## Blockchain
   * Amazon Managed Blockchain
   * Amazon QLDB (Quantum Ledger Database)
## Media Services
   * Amazon Elastic Transcoder
   * Amazon Interactive Video Service
   * Amazon Kinesis Video Streams
   * Amazon Nimble Studio
   * AWS Elemental Appliances & Software
   * AWS Elemental MediaConnect
   * AWS Elemental MediaLive
   * AWS Elemental MediaPackage
   * AWS Elemental MediaStore
   * AWS Elemental MediaTailor
## Business Applications
   * Alexa for Business
   * Amazon Chime
      * Meeting, video calls and chats
   * Amazon Chime SDK
   * Amazon Connect
   * Amazon Honeycode
   * Amazon WorkMail
      * Secure email and calendaring
   * AWS Supply Chain (Previe)
      * ML-powered supply chain application
   * AWS Wickr
## End User Computing
   * Amazon AppStream 2.0
      * Stream desktop applications to a browser
   * Amazon Workspaces Family
      * Virtual desktop services
## Migration and Transfer
## Game Tech
## Mobile
## Quantum Technologies
   * Amazon Braket
