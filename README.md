# Wanderlust - Your Ultimate Travel Blog 🌍✈️

# 🚀 End-to-End DevOps Implementation for a MERN Stack Application on AWS

![Preview Image](https://github.com/krishnaacharyaa/wanderlust/assets/116620586/17ba9da6-225f-481d-87c0-5d5a010a9538)
#

## 📖 Overview

This project demonstrates the complete DevOps lifecycle by automating the build, security scanning, testing, containerization, deployment, and monitoring of a production-style MERN Stack application on AWS.

The entire workflow follows modern DevOps practices, beginning with source code management in GitHub and ending with automated deployments to Amazon EKS using GitOps principles through ArgoCD.

The project emphasizes Infrastructure as Code, CI/CD automation, DevSecOps, Kubernetes orchestration, container security, and observability.

### <mark>Project Deployment Flow:</mark>
<img src="https://github.com/DevMadhup/Wanderlust-Mega-Project/blob/main/Assets/DevSecOps%2BGitOps.gif" />

## ✨ Key Highlights

- GitHub (Code)
- Infrastructure provisioning using Terraform
- AWS EC2 and Amazon EKS deployment
- Complete CI/CD pipeline with Jenkins
- Shared Jenkins Libraries
- SonarQube Static Code Analysis
- OWASP Dependency Check
- Trivy Filesystem & Container Image Scanning
- Docker Image Build & Push
- GitOps deployment using ArgoCD
- Kubernetes deployment with Helm
- Prometheus & Grafana Monitoring
- Automated Environment Configuration
- Integrated automatic email notification on success or failure of pipeline


### How pipeline will look after deployment:
- <b>CI pipeline to build and push</b>
![image](https://github.com/user-attachments/assets/20542d8b-0701-43ed-b2f8-82f8ed28d053)

- <b>CD pipeline to update application version</b>
![image](https://github.com/user-attachments/assets/8fd13807-622e-45f7-af23-dcc1ba30ca5d)

- <b>ArgoCD application for deployment on EKS</b>
![image](https://github.com/user-attachments/assets/1ea9d486-656e-40f1-804d-2651efb54cf6)

# Architecture
```text
GitHub
   │
   ▼
Jenkins CI
   │
   ├── Trivy FS Scan
   ├── OWASP Dependency Check
   ├── SonarQube Analysis
   ├── Docker Build
   ├── Trivy Image Scan
   └── Docker Push
        │
        ▼
GitOps Repository
        │
        ▼
ArgoCD
        │
        ▼
Amazon EKS
        │
        ▼
Prometheus + Grafana
```
# Technology Stack
Category	        Technologies
Cloud           	AWS EC2, Amazon EKS
IaC             	Terraform
SCM	              Git, GitHub
CI/CD	            Jenkins
Containers       	Docker
Orchestration	    Kubernetes
GitOps	          ArgoCD
Security	        Trivy, OWASP Dependency Check
Mail              Gmail 
Code Quality	    SonarQube
Monitoring      	Prometheus, Grafana
Registry	        Docker Hub
Application     	MERN Stack

```text
# CI/CD Workflow
Developer
      │
      ▼
GitHub Repository
      │
      ▼
Jenkins Pipeline
      │
      ├── Source Checkout
      ├── Dependency Installation
      ├── Trivy Filesystem Scan
      ├── OWASP Dependency Check
      ├── SonarQube Analysis
      ├── Quality Gate
      ├── Docker Image Build
      ├── Trivy Image Scan
      ├── Docker Push
      └── Update GitOps Repository
                    │
                    ▼
               ArgoCD Sync
                    │
                    ▼
               Amazon EKS
                    │
                    ▼
      Prometheus + Grafana Monitoring
```
## 📚 What I Learned

- Designing production-style CI/CD pipelines
- Managing Kubernetes deployments using GitOps
- Automating cloud infrastructure provisioning
- Integrating security into the CI pipeline
- Implementing monitoring and alerting
- Managing Docker images and registries
- Troubleshooting Jenkins pipelines and Kubernetes deployments

## 🔐 Security & Code Quality
### 🔍 SonarQube Code Quality Analysis
![SonarQube Dashboard](Assets/images/sonarqube.png)

### ✅ SonarQube Quality Gate Passed
![Sonarqube gates](Assets/images/gates.png)


## ☸️ Kubernetes & GitOps
### 🔄 ArgoCD GitOps Deployment Status
![SonarQube Dashboard](Assets/images/argocd.png)

### ☸️ Kubernetes Pods Running Successfully &  🌐 Kubernetes Services & Networking
![SonarQube Dashboard](Assets/images/get_all.png)

### ☁️ Amazon EKS Cluster Nodes
![SonarQube Dashboard](Assets/images/cluster.png)


## 📊 Monitoring & Observability

### 📊 Grafana Monitoring & Observability Dashboard
![image](https://github.com/user-attachments/assets/13321ee5-5d7b-4976-b409-25d3b865a42a)
![image](https://github.com/user-attachments/assets/75a22e4b-ae81-4cad-9c92-21dd90d126a8)



## ☁️ Infrastructure
### ☁️ AWS Cloud Infrastructure
![SonarQube Dashboard](Assets/images/aws.png)

## 🚀 Application
### 🚀 Application Successfully Deployed
![image](https://github.com/user-attachments/assets/06f9f1c8-094d-4d9f-a9d8-256fb18a9ae4)
![image](https://github.com/user-attachments/assets/64394f90-8610-44c0-9f63-c3a21eb78f55)

