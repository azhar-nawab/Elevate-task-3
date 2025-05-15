This repository contains the solution for provisioning a Docker container using Terraform on an AWS t2.micro Ubuntu instance.

Task Overview
Objective: Provision a local Docker container using Terraform.
Tools: Terraform, Docker.
Deliverables: main.tf, execution logs.
Steps Performed
Set up an Ubuntu t2.micro instance with Docker and Terraform.
Wrote main.tf to provision an Nginx container.
Executed:
terraform init (see init.log)
terraform plan (see plan.log)
terraform apply (see apply.log)
terraform state list (see state.log)
terraform destroy (see destroy.log)
Verified the container with docker ps and curl localhost:8080.
Files
main.tf: Terraform configuration file.
init.log: Terraform initialization log.
plan.log: Terraform plan log.
apply.log: Terraform apply log.
state.log: Terraform state list log.
destroy.log: Terraform destroy log.
Outcome
Successfully provisioned and destroyed an Nginx container using Infrastructure as Code principles with Terraform.
git commit -m "Add content"
