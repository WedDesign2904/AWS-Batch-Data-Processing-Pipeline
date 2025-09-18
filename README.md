# AWS-Batch-Data-Processing-Pipeline
Stores raw data in S3, uses Glue for ETL and schema cataloging, Athena for SQL queries, QuickSight for dashboards, and CloudWatch for monitoring and alerting, enabling scalable, cost-effective batch analytics.

𝐑𝐞𝐪𝐮𝐢𝐫𝐞𝐦𝐞𝐧𝐭𝐬
---

1️⃣ AWS Account

- Active AWS account with access to:
  - **Amazon S3** (for data storage)
  - **AWS Glue** (for ETL and schema discovery)
  - **Amazon Athena** (for SQL queries)
  - **Amazon QuickSight** (for dashboards)
  - **Amazon CloudWatch** (for logs and monitoring)
  - **IAM** (to create roles and policies)

2️⃣ IAM Roles & Policies  

- **IAM Role for Glue** with:
  - S3 read/write permissions (raw + processed buckets)
  - Glue service permissions  
- **IAM Role for Athena** with:
  - S3 access for query results  
  - Glue Data Catalog read permissions  
- **IAM Role for QuickSight** (or use federated access)

Getting Started
