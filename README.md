# Cloud & DevOps Engineering Internship 🚀

<p align="center">
  <img src="https://img.shields.io/badge/Cloud-AWS%20%2F%20Azure-orange?style=for-the-badge&logo=cloud&logoColor=white" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/CI%2FCD-GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
</p>

## Overview
Welcome to my official **Cloud & DevOps Engineering Internship** repository, completed as part of the Skill Set Go EduTech track. This repository showcases a comprehensive, hands-on journey through modern infrastructure engineering, containerization, Infrastructure as Code (IaC), container orchestration, and production-grade system monitoring.

---

## 📂 Repository Structure

```text
.
├── Week1_Linux/          # Linux system administration, permissions, and shell scripting
├── Week1_Cloud/          # Cloud fundamentals, AWS/Azure core services, and architecture notes
├── Week2-Docker/         # Containerization, multi-container Docker Compose apps, and Dockerfiles
├── Week3-Terraform/      # Infrastructure as Code using Terraform and LocalStack simulation
├── Week4-Kubernetes/     # K8s deployments, services, NodePort configuration, and ConfigMaps
└── capstone/             # Final capstone project consolidation and production layout
    ├── terraform/        # Provisioned IaC modules
    ├── docker/           # Optimized container build files
    ├── kubernetes/       # Scalable deployment and configuration manifests
    ├── ARCHITECTURE.md   # High-availability production architecture design
    └── README.md         # Capstone execution guide
🛠️ Key Technical Competencies Demonstrated
Infrastructure Provisioning (IaC): Utilized Terraform to automate local and cloud infrastructure resources (VPC, subnets, EC2, storage buckets via LocalStack).

Containerization & Workflows: Built, tagged, and orchestrated multi-container architectures using Docker and Docker Compose.

Container Orchestration (Kubernetes): Deployed and managed multi-replica applications in Minikube, resolving port conflicts and handling rolling updates.

Configuration & Monitoring: Configured Kubernetes ConfigMaps for runtime environment injection and leveraged kubectl top with the metrics server for real-time resource utilization tracking.

Architecture Design: Authored formal high-availability production architecture documents mapping out fault tolerance, load balancing, and secure cluster design.

🚀 Quick Start / Capstone Demo
To test and deploy the capstone Kubernetes manifests locally:

Clone the repository:

Bash
git clone [https://github.com/MuhammadIslahUddin/SkillSetGo_Cloud-DevOps-Internship.git](https://github.com/MuhammadIslahUddin/SkillSetGo_Cloud-DevOps-Internship.git)
cd SkillSetGo_Cloud-DevOps-Internship/capstone
Verify cluster status & apply manifests:

Bash
kubectl cluster-info
kubectl apply -f kubernetes/
Check running resources:

Bash
kubectl get all
kubectl top pods
👤 Author
Muhammad Islah Uddin

DevOps & Cloud Engineer

GitHub Profile
