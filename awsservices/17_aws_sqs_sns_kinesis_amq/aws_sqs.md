# **Amazon SQS (Simple Queue Service)**

## **Queue Types**
- **Standard Queues**
  - *At-least-once delivery*
  - *Best-effort ordering*
- **FIFO Queues**
  - *Exactly-once processing*
  - *First-In-First-Out delivery*

## **Key Features**
- *Fully managed service*
- *Scalable and reliable*
- **Decouples application components**
- **Supports server-side encryption (SSE)**
- **Dead-letter queues for message management**
- **Long polling(1sec to 20sec) and short polling**
- **Visibility timeout**

## **Queue Configuration**
- **Message retention period** (4 days , maximum up to 14 days)
- **Maximum message size** (up to 256 KB)
- **Delivery delay** (0 to 15 minutes)
- **Receive message wait time** (0 to 20 seconds)
- **Visibility timeout**

## **Integration**
- **AWS Lambda**
- **Amazon EC2**
- **Amazon ECS**
- **AWS Step Functions**
- **Other AWS services**

## **Security**
- **IAM for access control**
- **SQS Access Policies(smiliar to S3 bucket policies)**
- **VPC endpoints for enhanced network security**
- **Server-side encryption (SSE) with AWS KMS**
- **Client-side encryption**


## **Monitoring and Logging**
- **Amazon CloudWatch metrics**
- **AWS CloudTrail logs**

## **Best Practices**
- **Use appropriate queue type** (Standard vs FIFO)
- **Implement proper error handling**
- **Optimize polling**
- **Manage message lifecycle**
- **Implement security best practices**

## **Pricing**
- **Pay-per-use model**
- *Factors: requests, data transfer, optional features*

## **Additional Resources**
- [AWS SQS Documentation](https://docs.aws.amazon.com/sqs/)
- [AWS SQS Developer Guide](https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSDeveloperGuide/welcome.html)
- [AWS Architecture Blog on SQS](https://aws.amazon.com/blogs/architecture/category/messaging/amazon-simple-queue-service-sqs/)
- [Exploring the Power of AWS SQS: Messaging at Scale Deep Dive](https://cloudvisor.co/aws-guides/aws-sqs/)
- [AWS SQS and Decoupled Architectures: Benefits and Use Cases](https://www.deviq.io/insights/aws-sqs-decoupled-architecture)
