# AWS 3-Tier Architecture

## Architecture Diagram
![3-Tier Architecture Diagram](screenshots/architecture/3-tier-architecture-diagram.png)

## Project Overview
This project demonstrates a **secure, scalable, and highly available AWS 3-Tier Architecture**.

**Layers:**
- **Web Tier:** Handles HTTP/HTTPS requests
- **Application Tier:** Processes business logic
- **Database Tier:** Stores application data securely

The project uses multiple AWS services to build a production-style architecture.

## AWS Services Used
- Amazon EC2 (Web & App Servers)
- Amazon VPC, Subnets, Security Groups
- NAT Gateway
- Auto Scaling Groups & Launch Templates
- Application Load Balancers (ALB)
- Amazon RDS (MySQL)
- Bastion Host for secure private access

## Key Learnings & Challenges
- Implemented **high availability** using Multi-AZ deployment.
- Configured secure private subnet communication using **NAT Gateway**.
- Learned **Auto Scaling policies** and ALB configuration.
- Secured private instance access using **Bastion Host** and **SSH Agent Forwarding**.
