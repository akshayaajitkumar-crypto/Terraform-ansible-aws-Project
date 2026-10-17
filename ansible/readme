# Terraform and Ansible AWS Automation Project

## Project Overview
This project automates the provisioning and configuration of an AWS EC2 instance using **Terraform and Ansible**. Terraform provisions the AWS infrastructure, while Ansible configures the server and deploys an Apache web server.

## Technologies Used
- **AWS EC2** – Virtual server hosting
- **Terraform** – Infrastructure provisioning using Infrastructure as Code (IaC)
- **Ansible** – Configuration management and automated software installation
- **Python and Boto3** – AWS dynamic inventory management
- **Linux / Bash** – Automation scripts and command-line operations
- **Git and GitHub** – Version control and source code management

## Workflow
1. Terraform provisions an EC2 instance in AWS.
2. Terraform outputs the instance's public IP address.
3. Ansible dynamically discovers the EC2 instance using an AWS inventory script.
4. Ansible connects to the instance over SSH.
5. Ansible installs and configures Apache.
6. Automation scripts coordinate the deployment process.

## Key Features
- Infrastructure provisioning through Terraform.
- Automated server configuration using Ansible.
- Dynamic AWS EC2 inventory discovery.
- Bash-based deployment automation.
- Reusable and version-controlled infrastructure code.

## Project Structure
```text
project-2/
├── .gitignore
├── terraform/
│   ├── main.tf
│   ├── outputs.tf
│   ├── deploy.sh
│   └── .terraform.lock.hcl
└── ansible/
    ├── apache.yml
    ├── inventory.py
    └── run_ansible.sh
```

## Learning Outcomes
This project demonstrates practical experience with Infrastructure as Code, AWS resource provisioning, configuration management, dynamic inventory, and end-to-end DevOps automation.

## Security
AWS credentials and private keys should never be hardcoded or committed to GitHub. Use AWS CLI profiles, environment variables, or IAM roles where appropriate, and keep Terraform state files and sensitive configuration files out of version control.
