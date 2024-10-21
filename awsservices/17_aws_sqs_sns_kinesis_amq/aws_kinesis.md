# **AWS Kinesis**

## **Core Components**
- **Kinesis Data Streams**
- **Kinesis Data Firehose**
- **Kinesis Data Analytics**
- **Kinesis Video Streams**

## **Kinesis Data Streams**
- **Real-time data streaming**
- **Scalable and durable**
- **Shards for parallel processing**
- **Producers**
  - *AWS SDK*
  - *Kinesis Producer Library (KPL)*
  - *Kinesis Agent*
- **Consumers**
  - *Kinesis Client Library (KCL)*
  - *AWS Lambda*
  - *Kinesis Data Analytics*
  - *Kinesis Data Firehose*

## **Kinesis Data Firehose**
- **Fully managed service**
- **Near Real Time - Data written in batches**
- **Load streaming data into destinations**
- **Sources**
  - *Kinesis Data Streams*
  - *Amazon CloudWatch(Log & Events)*
  - *AWS IoT*
  - *SDK*
  - *Kinesis Agent*
- **Destinations**
  - *Amazon S3*
  - *Amazon Redshift*
  - *Amazon Elasticsearch Service*
  - *Splunk,Datadog,New Relic*
  - *HTTP Endpoint*
- **Data transformation with Lambda**

## **Kinesis Data Analytics**
- **Real-time analytics on streaming data**
- **SQL queries**
- **Java applications**
- **Input sources**
  - *Kinesis Data Streams*
  - *Kinesis Data Firehose*
- **Output destinations**
  - *Kinesis Data Streams*
  - *Kinesis Data Firehose*

## **Kinesis Video Streams**
- **Ingest and process video streams**
- **Real-time and batch video analytics**
- **Integration with AWS services**
  - *Amazon Rekognition*
  - *AWS SageMaker*

## **Common Use Cases**
- **Log and event data collection**
- **Real-time analytics**
- **Mobile data capture**
- **IoT data processing**
- **Video streaming and analysis**

## **Security and Compliance**
- **Encryption at rest and in transit**
- **IAM integration for access control**
- **VPC support**
- **AWS CloudTrail integration**

## **Monitoring and Management**
- **Amazon CloudWatch metrics**
- **AWS CloudFormation support**
- **AWS Management Console**
- **AWS CLI and SDKs**

## **Additional Resources**
- [Architecture overview - Streaming Data Solution for Amazon Kinesis](https://docs.aws.amazon.com/solutions/latest/streaming-data-solution-for-amazon-kinesis/architecture.html)
- [Architectural patterns for real-time analytics using Amazon Kinesis Data Streams, part 1](https://aws.amazon.com/blogs/big-data/architectural-patterns-for-real-time-analytics-using-amazon-kinesis-data-streams-part-1/)
- [Architectural Patterns for real-time analytics using Amazon Kinesis Data Streams, Part 2: AI Applications](https://aws.amazon.com/blogs/big-data/architectural-patterns-for-real-time-analytics-using-amazon-kinesis-data-streams-part-2-ai-applications/)
- [Amazon Kinesis | AWS Cheat Sheet - Digital Cloud Training](https://digitalcloud.training/amazon-kinesis/)
- [AWS EMR And Kinesis: Big Data Architectures Demystified](https://awstrain.com/aws-emr-and-kinesis-big-data-architectures-demystified/)
