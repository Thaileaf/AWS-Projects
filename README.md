# AWS-Projects

A collection of AWS Projects created for the K12 STEM Center. These hands-on tutorials teach students through building practical applications on Amazon Web Services, which they can then put on their own portfolios.

You can view/download all projects from my Google Drive as well:

[Google Drive](https://drive.google.com/drive/folders/1kRm1b-QOAsBYkRzkdwFVH9yk67CosjJX?usp=sharing)

## Projects Overview

This repository contains step-by-step guides for building the following AWS applications:

### 1. Minecraft Server with CloudWatch Monitoring

**Description:** Create a Minecraft Java Edition server with real-time player activity monitoring using CloudWatch.

**Skills learned:**
- Setting up AWS Lightsail instances
- Configuring CloudWatch monitoring
- Creating log processing pipelines with Lambda
- Building web dashboards for real-time monitoring

**AWS Services:** Lightsail, CloudWatch, Lambda, EC2, VPC

[View Tutorial →](./Proj-1-Minecraft-Server/)

---

### 2. Jellyfin Netflix-Like Media Server

**Description:** Build a secure, scalable media server using Jellyfin with HTTPS access and S3 storage integration.

**Skills learned:**
- Configuring VPC networking with public/private subnets
- Setting up Application Load Balancers with HTTPS
- Managing EBS volumes for high-performance storage
- Creating EC2 images for scaling and backup
- Integrating S3 for media management

**AWS Services:** EC2, VPC, ALB, S3, EBS, IAM

[View Tutorial →](./Proj-2-Netflix-Like-Media-Server/)

---

### 3. Email Masking Service

**Description:** Create a serverless email masking service that protects your real email address while allowing you to receive messages.

**Skills learned:**
- Domain registration and DNS configuration
- Setting up email receiving with SES
- Building serverless applications with Lambda
- Using DynamoDB for application data
- S3 integration for email archival

**AWS Services:** Route 53, SES, Lambda, DynamoDB, S3

[View Tutorial →](./Proj-3-Mail-Mask/)

---

### 4. Portfolio

**Description:** Deploy a personal portfolio website using S3 static website hosting. This will consist of multiple parts, with each part ending in a complete project while adding extra features.

Part 1: Static Website Hosting

Set up S3 static website hosting
Configure bucket policies for public access
Upload and organize portfolio files
Test and troubleshoot website delivery

Part 2: Database Integration with RDS

Create VPC with custom network configuration
Launch EC2 instance with Python web server
Set up MySQL database with Amazon RDS
Implement form submission with database storage
Configure security groups for proper access

Part 3: API Gateway and VPC Link

Create API Gateway for secure traffic management
Implement VPC Link for enhanced security
Set up HTTPS-enabled endpoints
Protect EC2 instance from direct internet exposure
Create custom routes for form submissions

Part 4: Serverless Backend with Lambda

Create Lambda functions for form processing
Connect Lambda to RDS database
Configure function URLs for public access
Implement environment variables for secure configuration
Test and troubleshoot serverless implementation

Part 5: Content Delivery with CloudFront

Implement global content delivery with CloudFront
Enable HTTPS for secure client connections
Configure caching for improved performance
Test and measure load time improvements
Compare regional performance differences

**Skills learned:**
Multi-tier web application architecture
Database integration and management
API design and security
Serverless computing patterns
Content delivery optimization
Progressive enhancement methodology

**AWS Services:** S3, IAM, VPC, EC2, RDS, API Gateway, Lambda, CloudFront

[View Tutorial →](./Proj-4-Portfolio/)

---

## Getting Started

### Prerequisites

To complete these projects, you'll need:

1. An AWS account (Free tier eligible for most components)
2. Basic familiarity with cloud concepts
3. A computer with internet access
4. Project-specific requirements listed in each tutorial

### Repository Structure

Each project is contained in its own directory with:

- A pdf with all of the step by step instructions
- Configuration files and code samples when needed

## Cost Considerations

These projects are designed to minimize costs while providing valuable learning experiences:

- Most parts components qualify for the AWS Free Tier
- Cost estimates are provided for each project
- Instructions include clean-up steps to avoid unexpected charges
- Projects can be completed in 1-2 hours to limit resource usage

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the K12 STEM Center for supporting cloud education
- Special appreciation to all contributors who helped refine these tutorials
