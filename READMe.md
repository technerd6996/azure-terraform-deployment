# Terraform Azure Infrastructure Deployment

## Overview

This project demonstrates Infrastructure as Code (IaC) principles using Terraform to provision and manage Microsoft Azure resources. The infrastructure is deployed through reusable Terraform configurations and is designed to be integrated with GitHub Actions for automated CI/CD workflows.

The goal of this project is to build a scalable, repeatable, and version-controlled cloud infrastructure deployment pipeline while following DevOps and Infrastructure as Code best practices.

## Architecture

The following Azure resources are provisioned:

* Resource Group
* Virtual Network (VNet)
* Subnet
* Network Security Group (NSG)
* Public IP Address
* Network Interface
* Linux Virtual Machine
* Storage Account (for Terraform Remote State)
* GitHub Actions CI/CD Pipeline

## Technologies Used

### Cloud Platform

* Microsoft Azure
* AWS

### Infrastructure as Code

* Terraform

### Version Control

* Git
* GitHub

### CI/CD

* GitHub Actions

### Operating System

* Ubuntu Server

## Project Structure

```text
terraform/
├── main.tf
├── variables.tf
├── outputs.tf
├── providers.tf
├── terraform.tfvars
└── .terraform.lock.hcl
```

## Features

* Infrastructure provisioning using Terraform
* Version-controlled infrastructure definitions
* Automated deployment workflow support
* Modular and reusable Terraform configurations
* Azure cloud resource management
* Remote state support
* Secure credential management through GitHub Secrets

## Deployment Workflow

1. Developer pushes code to GitHub.
2. GitHub Actions validates Terraform configuration.
3. Terraform plan is generated.
4. Infrastructure changes are reviewed.
5. Terraform apply provisions Azure resources.
6. Outputs are generated for verification.

## Learning Outcomes

Through this project, I gained hands-on experience with:

* Terraform fundamentals
* Azure resource provisioning
* Infrastructure as Code design principles
* State management
* Azure authentication and authorization
* GitHub Actions CI/CD pipelines
* Cloud infrastructure automation
* Version-controlled infrastructure deployments

## Future Enhancements

* Modular Terraform architecture
* Multi-environment deployments (Dev, Test, Prod)
* Terraform remote backend configuration
* Automated security scanning
* Cost estimation integration
* Monitoring and logging integration
* Azure Key Vault integration

## Author

Veda Vidyadaran

Senior Windows & VMware Analyst with 5+ Years of Experience | SRE | Cloud Infrastructure & Automation

Portfolio: https://portfolio-five-opal-hlh1gnjzc9.vercel.app 
GitHub: https://github.com/technerd6996
