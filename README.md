Tasks - Terraform Configuration
This repository contains Terraform scripts to provision and manage AWS resources.

Features
AWS EC2 Instance: Configured with security groups for SSH access.

Terraform Infrastructure as Code: Automated provisioning using Terraform.

Modular Configuration: Variables for easy configuration and deployment.

Files
main.tf: Defines AWS resources like EC2 instances and security groups.

variables.tf: Contains configurable variables like instance type, AMI, and more.

outputs.tf: Output values after resources are created.

Usage
Clone this repository.

Initialize Terraform:

bash
Copy
Edit
terraform init
Apply the configuration:

bash
Copy
Edit
terraform apply
Enter 'yes' to confirm the changes.
