# Cloud & DevOps Internship Capstone Project

## Overview
This repository contains the final Capstone project for the Skill Set Go EduTech Cloud & DevOps Internship track. It integrates infrastructure provisioning, containerization, Kubernetes orchestration, and monitoring into a single production-ready workflow.

## Project Structure
- `terraform/`: Infrastructure as Code (Terraform & LocalStack) provisioning VPC, subnets, and compute/storage resources.
- `docker/`: Containerized application build configurations.
- `kubernetes/`: Kubernetes manifests including Deployments, Services, and ConfigMaps with resource limits and metrics enabled.
- `ARCHITECTURE.md`: Detailed high-availability deployment architecture documentation.

## Quick Start
1. Provision infrastructure using Terraform.
2. Build and push container images.
3. Apply Kubernetes manifests to your cluster:
   ```bash
   kubectl apply -f kubernetes/
