# Terraform Project 1 - AWS EC2 Instance Deployment

##  Project Overview

This project demonstrates how to use Terraform to provision AWS infrastructure using Infrastructure as Code (IaC).

The project creates:
 An EC2 instance
 A Security Group
 Automatically fetches the latest Amazon Linux 2023 AMI
 Uses variables for reusable configuration
 Displays useful outputs such as Instance ID and Public IP



##  Technologies Used

- Terraform
- AWS EC2
- AWS Security Groups
- Amazon Linux 2023
- AWS CLI

##  Project Structure

```
terraform-project1/
│
├── main.tf
├── variables.tf
├── terraform.tfvars
├── outputs.tf
└── README.md


##  Features

- Creates an EC2 instance using Terraform
- Creates a Security Group
- Allows SSH (22) and HTTP (80)
- Uses reusable variables
- Retrieves the latest Amazon Linux AMI automatically
- Displays EC2 details after deployment

---

##  Prerequisites

Before running this project, make sure you have:

- Terraform installed
- AWS CLI installed
- AWS account
- IAM user with required permissions
- AWS Key Pair
- Configured AWS credentials (`aws configure`)

---

##  Deployment Steps

Initialize Terraform

```bash
terraform init
```

Format the configuration

```bash
terraform fmt
```

Validate the configuration

```bash
terraform validate
```

Preview the infrastructure

```bash
terraform plan
```

Create the infrastructure

```bash
terraform apply
```

Destroy the infrastructure

```bash
terraform destroy
```

---

##  Outputs

After deployment, Terraform displays:

- EC2 Instance ID
- Public IP Address
- Public DNS Name

---

## Concepts Learned

- Infrastructure as Code (IaC)
- Terraform Providers
- Variables
- Data Sources
- AWS EC2
- Security Groups
- Outputs
- Terraform Workflow

---

## Author

**Vangalu Manasa**

Learning AWS & DevOps | Terraform Beginner Project
