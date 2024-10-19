```mermaid

graph TD
  A[AWS CloudFront]

  subgraph Core_Concept
    A1[Fast content delivery network (CDN)]
    A2[Global Distribution]
    A3[Securely delivers data, videos, applications, and APIs globally]
  end
  
  subgraph Key_Features
    B1[Low Latency - Reduces the time it takes to deliver content to users]
    B2[High Transfer Speeds - Ensures fast data transfer rates]
    B3[Global Reach - Delivers content to users worldwide]
    B4[Developer Friendly - Easy to integrate with other AWS services]
  end
  
  subgraph Integration_with_AWS_Services
    C1[Amazon S3 - Stores and serves content]
    C2[AWS Shield - Provides DDoS protection]
    C3[AWS WAF - Protects against web exploits]
    C4[Amazon Route 53 - DNS service for routing traffic to CloudFront]
  end
  
  subgraph Configuration
    D1[Origin]
      D2[EC2 instance]
      D3[ALB]
      D4[S3]
    D5[Distribution - Specifies how content is delivered]
    D6[Cache Behaviors - Rules that control how content is cached and served]
  end
  
  subgraph Monitoring_and_Logging
    E1[CloudWatch - Monitors performance and usage]
    E2[Access Logs - Records requests and responses for analysis]
  end
  
  subgraph Price_Classes
    F1[Price Class All]
    F2[Price Class 100]
    F3[Price Class 200]
  end
  
  subgraph Use_Cases
    G1[Website Acceleration - Speeds up the delivery of websites]
    G2[Video Streaming - Delivers high-quality video content]
    G3[Application Delivery - Distributes web applications and APIs]
    G4[Security - Provides DDoS protection and secure delivery]
  end
  
  A --> A1
  A --> A2
  A --> A3
  A --> B1
  A --> B2
  A --> B3
  A --> B4
  A --> C1
  A --> C2
  A --> C3
  A --> C4
  A --> D1
  D1 --> D2
  D1 --> D3
  D1 --> D4
  A --> D5
  A --> D6
  A --> E1
  A --> E2
  A --> F1
  A --> F2
  A --> F3
  A --> G1
  A --> G2
  A --> G3
  A --> G4

```