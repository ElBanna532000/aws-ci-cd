# aws-ci-cd
![309442244-b553e105-136d-4ce4-93ec-540809cdc6ee](https://github.com/ElBanna532000/aws-ci-cd/assets/131378687/6918fbdf-84c4-4742-871d-8c0a7bfc0594)

This repository contains components for setting up a CI/CD pipeline for a simple Java application using Docker, Kubernetes, Jenkins, and Terraform.

## Components

1. Simple Java Code
2. Dockerfile
3. Kubernetes manifests (`deployment.yaml` & `service.yaml`)
4. Jenkinsfile (CI & CD)
5. Terraform code

## Setup Steps

1. **Terraform Setup:**
   - Create 'Master-Server' & 'Node-Server' EC2 instances.
   - Configure software packages on each server.

2. **Establish Passwordless Connection:**
   - Set up SSH connection between servers.

3. **Jenkins Setup:**
   - Add necessary credentials.
   - Install required plugins.
   - Configure CI & CD pipelines in Jenkins.

4. **Automation:**
   - Trigger CI pipeline on GitHub changes.
   - Automate CD pipeline after successful CI build.

5. **Infrastructure Deletion:**
   - Destroy infrastructure using Terraform.
