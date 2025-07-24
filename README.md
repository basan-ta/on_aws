# Welcome to my repository! Here, I’ve documented some topics that I learned from DataCamp courses.
# AWS Cloud Infrastructure & Migration Strategies

This repository documents AWS cloud concepts and migration strategies based on comprehensive cloud training. The content aligns with AWS Well-Architected Framework best practices and enterprise migration methodologies.

## Table of Contents
- [AWS Well-Architected Framework](#aws-well-architected-framework)
- [Cloud Migration Strategies](#cloud-migration-strategies)
- [Key AWS Services](#key-aws-services)

## AWS Well-Architected Framework

The six pillars of AWS Well-Architected Framework provide guidance for building secure, high-performing systems:

### 🔒 Security
- Implement least-privilege access and automated security policies
- Leverage IAM, KMS, CloudTrail, and GuardDuty
- Enforce encryption (at rest/in transit) and VPC segmentation

### 💰 Cost Optimization
- Rightsize resources (EC2, RDS) and utilize Reserved Instances
- Adopt auto-scaling and Spot Instances
- Monitor spending via Cost Explorer and Budgets

### ⚡ Performance Efficiency
- Select optimal instance types and storage classes
- Implement caching (ElastiCache) and CDNs (CloudFront)
- Use serverless architectures (Lambda) for event-driven workloads

### ⚙️ Operational Excellence
- Automate deployments with CloudFormation and CodeDeploy
- Establish CI/CD pipelines
- Monitor with CloudWatch and implement incident response runbooks

### 🌱 Sustainability
- Optimize workload energy efficiency (Graviton instances)
- Leverage managed services (Lambda, Fargate)
- Measure carbon footprint via AWS Customer Carbon Footprint Tool

### 🛡️ Reliability
- Design fault-tolerant systems (multi-AZ deployments)
- Implement auto-recovery (EC2 Auto Scaling) and backups
- Conduct chaos testing for resilience validation

## Cloud Migration Strategies

### Cloud Adoption Framework (CAF)
Structured 6-perspective approach:
1. **Business** - Value realization
2. **People** - Organizational change
3. **Governance** - Control frameworks
4. **Platform** - Standardized environments
5. **Security** - Protection mechanisms
6. **Operations** - Runbook development

### Migration Tools & Services
| Service | Purpose | Use Case |
|---------|---------|----------|
| **AWS DMS** | Database migration | Minimal downtime migrations (SQL Server → Aurora) |
| **AWS Snow Family** | Physical data transfer | Petabyte-scale data transfers |
| **Migration Hub** | Migration tracking | Centralized application migration monitoring |
| **S3 Transfer Acceleration** | Fast data uploads | Cross-country large file transfers |

### Migration Workflow
1. **Assessment**: Cloud readiness evaluation
2. **Mobilization**: CAF alignment
3. **Migration**: 
   - Lift-and-shift (rehost) for quick wins
   - Refactor for cloud-native optimization
4. **Operation**: Continuous optimization

## Key AWS Services

| Service | Category | Key Features |
|---------|----------|--------------|
| **EC2** | Compute | Scalable virtual servers, multiple instance types |
| **Lambda** | Serverless | Event-driven, pay-per-use, automatic scaling |
| **RDS** | Databases | Managed relational DB (MySQL, PostgreSQL) |
| **DynamoDB** | NoSQL | Serverless, single-digit ms latency |
| **CloudFront** | Networking | Global CDN, DDoS protection |
| **S3** | Storage | Scalable object storage, 11 9's durability |

