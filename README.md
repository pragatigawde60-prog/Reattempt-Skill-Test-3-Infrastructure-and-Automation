# Reattempt-Skill-Test-3-Infrastructure-and-Automation



# Terraform AWS Nginx Deployment

This project demonstrates how to use **Infrastructure as Code (IaC)** using Terraform to provision an EC2 instance on Amazon Web Services and automatically deploy an Nginx web server.


## Project Overview

This Terraform project will:

* Create an AWS EC2 instance (Ubuntu)
* Configure Security Group (HTTP + SSH access)
* Install and start Nginx automatically using `user_data`
* Deploy a simple web page
* Output public IP for access


## Architecture

User → AWS EC2 (Ubuntu) → Nginx Web Server → Browser

## Files Included

main.tf        # Terraform configuration file
README.md      # Project documentation


## ⚙️ Prerequisites

Before running this project, ensure you have:

* AWS account
* AWS CLI configured (`aws configure`)
* Terraform installed
* Key pair (optional for SSH access)

## Deployment Steps
<img width="1912" height="927" alt="image" src="https://github.com/user-attachments/assets/3dfd6275-704a-4ef7-91a6-53389d83b0ea" />

### 1. Initialize Terraform

terraform init

### 2. Validate configuration

terraform validate

### 3. Preview resources

terraform plan

### 4. Deploy infrastructure

terraform apply
Yes
## 🌐 Access Application

After successful deployment, Terraform will output:
Open in browser:
http://15.206.173.121
You should see:
Terraform Nginx Server is Running
`

## 📤 Outputs

* Public IP of EC2 instance

<img width="1852" height="1112" alt="image" src="https://github.com/user-attachments/assets/ee718a7a-bcc7-4ef4-8e1f-106cb937cfdb" />

