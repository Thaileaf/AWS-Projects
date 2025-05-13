# AWS-Projects

A collection of AWS Projects created for the K12 STEM Center. These hands-on tutorials teach students through building practical applications on Amazon Web Services, which they can then put on their own portfolios.

You can view/download all projects from my Google Drive as well:

![Google Drive](https://drive.google.com/drive/folders/1kRm1b-QOAsBYkRzkdwFVH9yk67CosjJX?usp=sharing)

## Projects Overview

This repository contains step-by-step guides for building the following AWS-powered applications:

### 1. Minecraft Server with CloudWatch Monitoring

![Minecraft Server](https://raw.githubusercontent.com/your-username/AWS-Projects/main/images/minecraft-thumbnail.png)

**Description:** Create a Minecraft Java Edition server with real-time player activity monitoring using CloudWatch.

**Skills learned:**
- Setting up AWS Lightsail instances
- Configuring CloudWatch monitoring
- Creating log processing pipelines with Lambda
- Building web dashboards for real-time monitoring

**AWS Services:** Lightsail, CloudWatch, Lambda, EC2, VPC

[View Tutorial →](./minecraft-server/)

---

### 2. Jellyfin Media Server

![Jellyfin Media Server](https://raw.githubusercontent.com/your-username/AWS-Projects/main/images/jellyfin-thumbnail.png)

**Description:** Build a secure, scalable media server using Jellyfin with HTTPS access and S3 storage integration.

**Skills learned:**
- Configuring VPC networking with public/private subnets
- Setting up Application Load Balancers with HTTPS
- Managing EBS volumes for high-performance storage
- Creating EC2 images for scaling and backup
- Integrating S3 for media management

**AWS Services:** EC2, VPC, ALB, S3, EBS, IAM

[View Tutorial →](./jellyfin-server/)

---

### 3. Email Masking Service

![Email Masking](https://raw.githubusercontent.com/your-username/AWS-Projects/main/images/email-masking-thumbnail.png)

**Description:** Create a serverless email masking service that protects your real email address while allowing you to receive messages.

**Skills learned:**
- Domain registration and DNS configuration
- Setting up email receiving with SES
- Building serverless applications with Lambda
- Using DynamoDB for application data
- S3 integration for email archival

**AWS Services:** Route 53, SES, Lambda, DynamoDB, S3

[View Tutorial →](./email-masking/)

---

### 4. Static Website Hosting

![Static Website](https://raw.githubusercontent.com/your-username/AWS-Projects/main/images/website-thumbnail.png)

**Description:** Deploy a personal portfolio website using S3 static website hosting.

**Skills learned:**
- Configuring S3 buckets for web hosting
- Setting up proper IAM policies
- Managing file uploads to S3
- Enabling public web access securely

**AWS Services:** S3, IAM

[View Tutorial →](./static-website/)

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

- A PDF with all of the step by step instructions
- Configuration files and code samples when applicable

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
