# Kinesis Data Streams vs Data Firehose

## Kinesis Data Streams
- **Real-time data streaming service**
- **Custom processing and analysis**
- **Scalable and durable**
- **Pay per shard**
- **Components**
  - Shards
  - Partition Keys
  - Sequence Numbers
- **Use cases**
  - Real-time analytics
  - Log and event data intake
  - Mobile data capture
- **Integration**
  - Custom applications
  - AWS Lambda
  - Kinesis Data Analytics
- **Scaling**
  - Manual shard splitting and merging
- **Data retention**
  - Configurable (24 hours to 365 days)

## Amazon Data Firehose
- **Fully managed data delivery service**
- **Automatic scaling and management**
- **Pay for data processed**
- **Destinations**
  - Amazon S3
  - Amazon Redshift
  - Amazon OpenSearch Service
  - Splunk
  - Custom HTTP endpoints
- **Data transformation**
  - Format conversion (e.g., to Parquet, ORC)
  - Lambda functions for custom processing
- **Use cases**
  - Data lake creation
  - ETL jobs
  - Analytics and BI
- **Integration**
  - Kinesis Data Streams
  - CloudWatch Logs
  - IoT Core
- **Scaling**
  - Automatic
- **Data retention**
  - Transient (delivers to destination)

## Key Differences
- **Processing**
  - Streams: Custom processing
  - Firehose: Managed delivery and optional transformation
- **Scalability**
  - Streams: Manual shard management
  - Firehose: Automatic scaling
- **Use cases**
  - Streams: Real-time processing and custom analytics
  - Firehose: Data delivery to AWS services and supported endpoints
- **Pricing model**
  - Streams: Per shard
  - Firehose: Per data processed

## Additional Resources
- [AWS Kinesis Data Streams Overview](https://aws.amazon.com/kinesis/data-streams/)
- [AWS Kinesis Data Firehose Overview](https://aws.amazon.com/kinesis/data-firehose/)
- [Building Real-Time Data Processing Applications with Amazon Kinesis](https://aws.amazon.com/blogs/big-data/building-real-time-data-processing-applications-with-amazon-kinesis)