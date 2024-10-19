---
title: CloudFront
CloudFront:
  colorFreezeLevel: 2
---



## Core Concept:
- Fast content delivery network (CDN)
- Global Distribution
- Securely delivers data, videos, applications, and APIs globally

## Key Features
- Low Latency -  Reduces the time it takes to deliver content to users
- High Transfer Speeds -  Ensures fast data transfer rates
- Global Reach -  Delivers content to users worldwide
- Developer Friendly - Easy to integrate with other AWS services

## Integration with AWS Services

- Amazon S3: Stores and serves content
- AWS Shield: Provides DDoS protection
- AWS WAF: Protects against web exploits
- Amazon Route 53: DNS service for routing traffic to CloudFront

## Configuration:

- Origin: The source of the content
   - ec2 instance
   - alb 
   - s3 
- Distribution: The configuration that specifies how content is delivered
- Cache Behaviors: Rules that control how content is cached and served

## Monitoring and Logging:
- CloudWatch: Monitors performance and usage
- Access Logs: Records requests and responses for analysis

## Price Classes
 - Price Class All
 - Price Class 100
 - Price Class 200

 ## Use Cases:

- Website Acceleration: Speeds up the delivery of websites
- Video Streaming: Delivers high-quality video content
- Application Delivery: Distributes web applications and APIs
- Security: Provides DDoS protection and secure delivery