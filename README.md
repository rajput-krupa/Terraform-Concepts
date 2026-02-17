## Terraform 
As part of my Cloud & DevOps journey, I began learning Infrastructure as Code (IaC) and explored how Terraform simplifies infrastructure management.
Here's what I learned.
The Problem with Traditional Infrastructure:
Environment inconsistencies (dev ≠ prod)
Human errors
Time-consuming setups
Poor scalability

As systems grow, manual management becomes inefficient and risky.

## What is Infrastructure as Code (IaC)?
Provisioning and managing infrastructure using code instead of manual processes.
Instead of clicking through dashboards:
You define infrastructure in configuration files (.tf)
Store them in Git
Deploy using automation

## What is Terraform?
Terraform is an open-source IaC tool developed by HashiCorp.
It allows you to provision infrastructure across multiple cloud providers like:
Amazon Web Services
Microsoft Azure
Google Cloud

Terraform uses providers to interact with cloud APIs and manage resources declaratively.
## 🔄 Terraform Workflow
Terraform follows a simple lifecycle:
terraform init
terraform validate
terraform plan
terraform apply
terraform destroy
<img width="1000" height="422" alt="Screenshot 2026-02-16 at 7 48 53 PM" src="https://github.com/user-attachments/assets/b98335ba-a247-43c2-be94-ba669f02d34d" />

## 🔑 Key Takeaways
Infrastructure should be treated like software.
Automation ensures consistency across environments.
Terraform makes infrastructure scalable and version-controlled.
IaC is a foundational skill in DevOps and Cloud Engineering
