1.  **Compute Services:**
    
    *   **EC2 (Elastic Compute Cloud):**
        
        *   Virtual servers in the cloud, resizable and scalable.
        *   Various instance types optimized for different workloads (e.g., compute-optimized, memory-optimized).
        *   Key difference: Provides full control over the server, suitable for applications with specific requirements.
    *   **ECS (Elastic Container Service):**
        
        *   Docker container management service.
        *   Helps run, stop, and manage containers.
        *   Key difference: Simplifies containerized application deployment and management.
    *   **Lambda:**
        
        *   Serverless computing service.
        *   Run code in response to events without provisioning or managing servers.
        *   Key difference: Pay only for actual compute time, scales automatically.
2.  **Storage Services:**
    
    *   **S3 (Simple Storage Service):**
        
        *   Object storage with scalable and durable data storage.
        *   Key difference: Suitable for static website hosting, data archiving, and backup.
    *   **EBS (Elastic Block Store):**
        
        *   Persistent block storage for EC2 instances.
        *   Key difference: Provides storage volumes that can be attached to EC2 instances.
    *   **Glacier:**
        
        *   Low-cost archive storage.
        *   Key difference: Optimized for data archival and long-term backup.
3.  **Database Services:**
    
    *   **RDS (Relational Database Service):**
        
        *   Managed relational databases (MySQL, PostgreSQL, Oracle, SQL Server).
        *   Key difference: Automates common database tasks like backups, patch management.
    *   **DynamoDB:**
        
        *   Managed NoSQL database.
        *   Key difference: Provides seamless and automatic scalability for high-performance applications.
    *   **Aurora:**
        
        *   MySQL and PostgreSQL-compatible relational database.
        *   Key difference: Offers high performance and availability with automatic replication and failover.
    *   **DocumentDB**

        * Fully managed, scalable NoSQL database compatible with MongoDB.
        * Key difference: Managed NoSQL service for MongoDB compatibility, offering scalability and ease of use.
    * **ElastiCache**

        * In-memory data store service (Redis, Memcached).
        * Key difference: Improves application performance by caching frequently accessed data.
    * **Neptune**

        * Fully managed graph database service
        * Key Difference: Specialized for graph data and relationships, offering support for both Property Graph and RDF graph models.

    * **QLDB**

        *  Fully managed ledger database service for maintaining a transparent and immutable history of changes to application data.
        * Key Difference: Specialized for maintaining an immutable and transparent ledger of all changes to application data.
    *  **KeySpaces**

        * Managed Apache Cassandra-compatible database service.
        * Key Difference: A fully managed, serverless Cassandra-compatible database service designed for applications with NoSQL requirements
    * **TimeStream**

        * Managed time-series database designed for IoT, operational monitoring, and analytics workloads.
        * Key Difference: Specialized for time-series data storage and analytics, providing serverless scalability and retention policy management.
4.  **Networking:**
    
    *   **VPC (Virtual Private Cloud):**
        
        *   Isolated network within the cloud.
        *   Key difference: Provides control over the virtual networking environment.
    *   **Route 53:**
        
        *   Scalable and highly available domain name system (DNS).
        *   Key difference: Manages domain registration and routing traffic to resources.
    *   **CloudFront:**
        
        *   Content Delivery Network (CDN).
        *   Key difference: Distributes content globally with low latency and high data transfer speeds.
5.  **Security & Identity:**
    
    *   **IAM (Identity and Access Management):**
        
        *   User and access management.
        *   Key difference: Controls access to AWS resources with granular permissions.
    *   **Cognito:**
        
        *   User identity and authentication service.
        *   Key difference: Manages user identity for web and mobile apps.
    *   **KMS (Key Management Service):**
        
        *   Key storage and management.
        *   Key difference: Centralizes control over cryptographic keys used to protect data.
6.  **Management Tools:**
    
    *   **CloudWatch:**
        
        *   Monitoring and management service.
        *   Key difference: Collects and tracks metrics, monitors log files, and sets alarms.
    *   **CloudTrail:**
        
        *   Logs and monitors AWS account activity.
        *   Key difference: Records API calls for your AWS account and delivers log files.
    *   **Config:**
        
        *   AWS resource inventory and configuration history.
        *   Key difference: Provides a detailed view of changes to AWS resource configurations.
7.  **Developer Tools:**
    
    *   **CodeCommit:**
        
        *   Version control service.
        *   Key difference: Securely stores and manages assets in the cloud.
    *   **CodeBuild:**
        
        *   Fully managed build service.
        *   Key difference: Compiles source code, runs tests, and produces deployable software packages.
    *   **CodeDeploy:**
        
        *   Automates code deployment.
        *   Key difference: Deploys applications to a variety of compute services.
8.  **Analytics:**
    
    *   **Athena:**
        
        *   Query data in S3 using SQL.
        *   Key difference: Allows querying data without the need for a database.
    *   **EMR (Elastic MapReduce):**
        
        *   Big data processing framework.
        *   Key difference: Distributes data processing tasks across a resizable cluster of EC2 instances.
    *   **QuickSight:**
        
        *   Business intelligence service.
        *   Key difference: Easily creates and publishes interactive dashboards.
9.  **AI and Machine Learning:**
    
    *   **SageMaker:**
        
        *   Build, train, and deploy machine learning models.
        *   Key difference: Simplifies the process of building, training, and deploying ML models.
    *   **Comprehend:**
        
        *   Natural language processing.
        *   Key difference: Extracts insights and relationships from text.
    *   **Rekognition:**
        
        *   Image and video analysis.
        *   Key difference: Identifies objects, people, text, scenes, and activities in images and videos.
10. **Integration Services:**
    
    *   **SQS (Simple Queue Service):**
        
        *   Managed message queues.
        *   Key difference: Decouples components of a cloud application.
    *   **SNS (Simple Notification Service):**
        
        *   Publish/subscribe messaging service.
        *   Key difference: Sends messages or notifications to distributed systems.
    *   **SWF (Simple Workflow Service):**
        
        *   Coordinate distributed applications.
        *   Key difference: Helps coordinate tasks across distributed application components.
