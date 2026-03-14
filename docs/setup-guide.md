# Setup Guide – Serverless AWS Data Lake Automation Platform

This guide walks through a simple end‑to‑end setup in a single AWS account.

> Note: Replace all placeholder values like `<ACCOUNT_ID>`, `<REGION>`, `<BUCKET_NAME>` and ARNs with values from your environment.

## 1. Prerequisites

- AWS account with permissions for IAM, S3, Kinesis, Glue, Lambda, DynamoDB, API Gateway, Cognito, KMS, CloudWatch. [file:2][file:3]  
- AWS CLI installed and configured (`aws configure`).  
- Python 3.8+ for packaging Lambda and ETL scripts. [file:3]

Clone the repository:

```bash
git clone https://github.com/<your-username>/serverless-aws-data-lake-automation.git
cd serverless-aws-data-lake-automation
