# WGU-CloudFormation-Infrastructure-Example
This project is part of my AWS Cloud Capstone Project at Western Governor's University
It is meant to showcase a simple example of how a Managed Service Provider (MSP) - *CloudNet Technologies* can modernize its traditional, manual infrastructure deployment methodology by investing in Infrastructure as Code with AWS CloudFormation

## Project Overview
CloudNet Technologies has previously only deployed customer infrastructure manually, which was time consuming, costly, and error-prone.
Infrastructure as Code automates the process by provisioning a complete, production-grade AWS environment, with servers, databases, security, monitoring, and more, using a single CloudFormation Template.

The Template includes:
- **Compute**: Three EC2 instances running Apache HTTP servers, supported by an Auto-Scaling Group (ASG).
- **Networking**: Virtual Private Cloud with public and private subnets, NAT Gateway, Route Tables, and Internet Gateway.
- **Load Balancing**: Application Load Balancer (ALB) that distributes web traffic to EC2 instances.
- **Database**: Amazon RDS MySQL, as a relational database with encryption, subnet groups, with Secrets Manager Integration.
- **Storage**: S3 bucket with versioning, AES-256 server-side/at-rest encryption. Used for storing various company files.
- **Monitoring**: CloudWatch alarm for CPU Metrics, can be further customized depending on needs.
- **Security**: Security Groups, IAM Roles, and encrypted credentials via Secrets Manager.

---
