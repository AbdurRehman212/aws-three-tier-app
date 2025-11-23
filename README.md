# aws-three-tier-app
Production-style 3-tier AWS application with EC2, ALB, RDS, S3, and CloudWatch

# AWS Three-Tier Application

This project implements a production-style three-tier architecture on AWS:

- **Frontend / Entry**: Application Load Balancer (ALB)
- **Application Layer**: EC2 instances running a Python Flask app
- **Data Layer**: RDS (MySQL/PostgreSQL)
- **Static Assets**: S3
- **Monitoring & Logs**: CloudWatch

## Week 1 Goals

- Day 1: Set up repo, architecture diagram, first EC2 instance with a basic web app
- Day 2–6: Add load balancer, RDS, S3, monitoring, and documentation
