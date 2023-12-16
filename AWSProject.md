![Dummy-project](https://github.com/BoyNovr/Static-Assets/blob/main/project.drawio.png)

This lab is a component of the AWS re/Start POST Graduate program. It initiates by hosting a static website on Amazon S3, establishing an Amazon DynamoDB database, and configuring a REST API to facilitate communication among application components. Lambda functions play a role in retrieving data from the Amazon DynamoDB database. Additionally, another Lambda function is incorporated into an AWS Step Functions workflow, utilizing presigned URLs to acquire coffee bean information from a supplier.

The coffee website is seamlessly integrated with a new web application designed for the coffee supplier. Information regarding the coffee bean inventory sent by the supplier is obtained using Amazon SNS, subscribed to by Amazon SQS. This information can then be pulled by the application to provide real-time updates. The second application leverages a platform as a service, Amazon Elastic Beanstalk, with configured elastic load balancing directing traffic to an auto-scaling group for scalability.

To enhance database performance, Amazon ElastiCache with Memcached is configured to handle read operations, thereby reducing the load on the main database. Additionally, Amazon CloudFront is employed as a cache server in this project to minimize latency and ensure secure access using an SSL certificate.

Amazon Cognito serves as the authentication mechanism to ensure that only authorized users can access the reports.
