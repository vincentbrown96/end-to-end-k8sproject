<<<<<<< HEAD
# end-to-end-k8sproject
=======
# 🛠️ AWS EKS Project – Building and Deploying Kubernetes on AWS

## 🚀 Overview

This project demonstrates my hands-on experience setting up and managing a Kubernetes cluster using **Amazon EKS (Elastic Kubernetes Service)**. I walked through the full lifecycle — from environment setup and IAM permissions to deploying containerized applications on a scalable, secure EKS cluster.

It showcases my ability to work with **AWS, Kubernetes, Docker, IAM, networking**, and the **AWS CLI/kubectl**, simulating a real-world infrastructure setup.

---

## 📋 Table of Contents

1. [Project Goals](#project-goals)  
2. [Tech Stack](#tech-stack)  
3. [Key Concepts I Explored](#key-concepts-i-explored)  
4. [Step-by-Step Breakdown](#step-by-step-breakdown)  
   - AWS Account & IAM  
   - CLI & kubectl Configuration  
   - Networking & Security  
   - Cluster Creation  
   - App Deployment  
5. [Lessons Learned](#lessons-learned)  
6. [Screenshots (optional)](#screenshots-optional)  
7. [Next Steps / Improvements](#next-steps--improvements)

---

## ✅ Project Goals

- Understand Kubernetes architecture and how it integrates with AWS.
- Compare EKS with self-managed Kubernetes.
- Set up a secure and scalable Kubernetes cluster using AWS EKS.
- Deploy Dockerized applications using YAML manifests.
- Gain hands-on experience with IAM, VPC, Security Groups, and Load Balancers.

---

## 🧰 Tech Stack

- **Amazon EKS**
- **AWS CLI & IAM**
- **kubectl**
- **Docker**
- **YAML**
- **Amazon VPC, Subnets, Security Groups**
- **CloudWatch (for monitoring)**

---

## 📚 Key Concepts I Explored

- Managed vs Self-Managed Kubernetes (EKS Pros/Cons)
- IAM Policies, Roles, and Access Keys
- Kubernetes Deployments, Services, and Nodes
- Networking with VPCs, IGWs, and Route Tables
- Authenticating kubectl with EKS clusters
- Containerization with Docker

---

## 🧪 Step-by-Step Breakdown

### 1. AWS Environment & IAM Setup
- Created a fresh AWS account and IAM users with MFA for security.
- Configured programmatic access and access keys for CLI usage.

### 2. CLI Tools Setup
- Installed and configured **AWS CLI** and **kubectl** on my local machine.
- Verified CLI connectivity and updated my kubeconfig to point to EKS.

### 3. Networking Configuration
- Created a custom VPC with both public and private subnets.
- Set up Internet Gateway, Route Tables, and attached them appropriately.
- Built and applied Security Groups with fine-grained inbound/outbound rules.

### 4. Launching the EKS Cluster
- Deployed a new EKS cluster via the AWS Console and CLI.
- Configured IAM roles for the control plane and worker nodes.
- Connected to the EKS cluster using kubectl and verified node status.

### 5. Application Deployment
- Containerized a sample app using Docker.
- Wrote deployment and service YAML files for Kubernetes.
- Applied manifests and successfully deployed the app on the EKS cluster.

---

## 💡 Lessons Learned

- Setting up IAM roles and policies is essential and easy to overlook.
- EKS abstracts away a lot of operational overhead, but understanding the underlying components helps with debugging and scalability.
- Networking (VPC, subnets, security groups) is just as important as the cluster itself.
- Hands-on practice with `kubectl` boosts confidence in managing K8s workloads.

---

## 📈 Next Steps / Improvements

- Add CI/CD pipeline with GitHub Actions to automate deployments.
- Integrate monitoring with Prometheus & Grafana.
- Experiment with auto-scaling and cost optimization using spot instances.
>>>>>>> c3cd138 (Initial commit - upload project)
