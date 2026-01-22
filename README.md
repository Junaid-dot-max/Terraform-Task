# Terraform-Task
# Terraform Multi-Region EC2 Deployment

## Task Description
Launch Linux EC2 instances in two AWS regions using a single Terraform file.

## Tech Stack Used
- AWS EC2
- Terraform
- AWS CLI

## Regions Deployed
- us-east-1 (N. Virginia)
- ap-south-1 (Mumbai)

## Files
- main.tf      → Terraform configuration
- outputs.tf   → Instance IDs and Public IPs
- README.md    → Project documentation
- screenshots/ → Execution and AWS Console proof

## Terraform Commands Used
terraform init -upgrade  
terraform apply  
terraform destroy  

## Result
Successfully launched Linux EC2 instances in two AWS regions using a single Terraform configuration file with multiple providers.

## Author
Junaid
EOF
