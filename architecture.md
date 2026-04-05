# Architecture Overview

The platform integrates with AWS services to monitor and analyze cloud infrastructure.

## Components

- AWS CloudTrail → Logs API activity
- AWS Config → Tracks configuration changes
- AWS Lambda → Processes findings
- Amazon S3 → Stores logs and reports
- Amazon Bedrock → AI-based analysis

## Flow

1. Collect logs from CloudTrail and Config
2. Analyze configurations
3. Detect vulnerabilities
4. Generate remediation suggestions
