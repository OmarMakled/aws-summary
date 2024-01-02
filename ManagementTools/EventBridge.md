**Amazon EventBridge** 

is a serverless event bus service provided by Amazon Web Services (AWS). It enables you to build event-driven architectures and simplify the development of decoupled and scalable microservices.

By using AWS EventBridge, you can create loosely coupled architectures where different components of your application can communicate through events without direct dependencies.

**Overview:**

* Event Bus: Acts as a communication channel where events are sent and received.

* Events: Messages representing occurrences of interest within your applications.

* Event Sources: AWS services, integrated software, or custom applications that generate events.

* Event Rules: Define criteria for matching events and specify actions to take when a match occurs.

* Targets: Destinations for events, such as Lambda functions, SNS topics, SQS queues, etc.

Example:
Let's create a simple example where an S3 bucket triggers a Lambda function whenever a new object is created.

Schedule: Cron jobs to trigger script on Lambda function.