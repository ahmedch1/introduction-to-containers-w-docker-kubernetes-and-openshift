<div align="center">

# 🚀 Introduction to Containers w/ Docker, Kubernetes & OpenShift

### IBM Coursera Course - Lab Exercises

[![Course Rating](https://img.shields.io/badge/Rating-4.4★-yellow?style=for-the-badge)](https://www.coursera.org/learn/ibm-containers-docker-kubernetes-openshift)
[![Enrolled](https://img.shields.io/badge/Enrolled-143K+-blue?style=for-the-badge)](https://www.coursera.org/learn/ibm-containers-docker-kubernetes-openshift)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)
[![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)](https://kubernetes.io/)
[![OpenShift](https://img.shields.io/badge/OpenShift-EE0000?style=for-the-badge&logo=red-hat-open-shift&logoColor=white)](https://www.openshift.com/)

[Course Link](https://www.coursera.org/learn/ibm-containers-docker-kubernetes-openshift)

</div>

---

## 📋 Table of Contents

- [About the Course](#-about-the-course)
- [Course Details](#-course-details)
- [Technologies & Skills](#-technologies--skills)
- [Labs Overview](#-labs-overview)
- [What I Learned](#-what-i-learned)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [License](#-license)

---

## 📖 About the Course

This repository contains hands-on lab exercises from IBM's **[Introduction to Containers w/ Docker, Kubernetes & OpenShift](https://www.coursera.org/learn/ibm-containers-docker-kubernetes-openshift)** course on Coursera.

The course covers containerization fundamentals and teaches how to build cloud-native applications using Docker, Kubernetes, OpenShift, and Istio. Labs progress from basic Docker containerization through Kubernetes orchestration, including scaling, updates, and configuration management.

---

## 📊 Course Details

- **Level:** Intermediate
- **Duration:** 2 weeks (10 hours/week)
- **Modules:** 5
- **Rating:** 4.4/5 (1,003 reviews)
- **Students Enrolled:** 143,195+
- **Offered by:** IBM

---

## 🛠 Technologies & Skills

### Technologies Covered
- **Docker** - Containerization and image building
- **Kubernetes** - Container orchestration
- **OpenShift** - Red Hat's Kubernetes platform
- **Istio** - Service mesh for microservices
- **Node.js & Express.js** - Application runtime and framework

### Skills Gained
- Containerization
- Kubernetes orchestration
- Docker image building and management
- YAML configuration
- kubectl CLI
- Application deployment
- DevOps practices
- Cloud-native computing
- ConfigMaps and Secrets
- Scaling and updates
- CI/CD concepts
- Microservices architecture

---

## 🔬 Labs Overview

### Lab 1: Containers and Docker
- Building Docker images from Dockerfiles
- Running containerized applications
- Working with Docker CLI commands
- Pushing images to IBM Cloud Container Registry

**Tech:** Docker, Node.js, Express.js

---

### Lab 2: Introduction to Kubernetes
- Creating Kubernetes deployments (imperative vs declarative)
- Using `kubectl create` and `kubectl apply`
- Working with YAML manifests
- Understanding pods and deployments

**Tech:** Kubernetes, kubectl, Docker

---

### Lab 3: Kubernetes Scaling and Updates
- Using ConfigMaps for environment variables
- Scaling deployments
- Managing application configuration
- Deployment updates

**Tech:** Kubernetes, ConfigMaps, kubectl

---

## 🎯 What I Learned

**Docker & Containerization**
- Building Docker images with Dockerfiles
- Running and managing containers
- Working with container registries

**Kubernetes**
- Deploying applications with kubectl
- Creating and managing pods, deployments, and services
- Using YAML for declarative configuration
- Scaling applications

**Configuration Management**
- Using ConfigMaps for environment variables
- Separating configuration from code
- Managing application settings

**DevOps Concepts**
- Container orchestration
- Application deployment and scaling
- Infrastructure as Code with YAML

---

## 📁 Project Structure

```
CC201/
├── labs/
│   ├── 1_ContainersAndDocker/
│   │   ├── app.js                    # Express.js application
│   │   ├── Dockerfile                # Container image definition
│   │   └── package.json              # Node.js dependencies
│   │
│   ├── 2_IntroKubernetes/
│   │   ├── app.js                    # Express.js application
│   │   ├── Dockerfile                # Container image definition
│   │   ├── hello-world-create.yaml   # Imperative deployment manifest
│   │   ├── hello-world-apply.yaml    # Declarative deployment manifest
│   │   └── package.json              # Node.js dependencies
│   │
│   └── 3_K8sScaleAndUpdate/
│       ├── app.js                           # Express.js with env vars
│       ├── Dockerfile                       # Container image definition
│       ├── deployment.yaml                  # Basic deployment manifest
│       ├── deployment-configmap-env-var.yaml # Deployment with ConfigMap
│       └── package.json                     # Node.js dependencies
│
├── LICENSE                           # Apache 2.0 License
└── README.md                         # This file
```

---

## 🚀 Getting Started

### Prerequisites
- Docker
- Kubernetes cluster (Minikube, Docker Desktop, or cloud provider)
- kubectl CLI
- Node.js (for local development)

### Quick Start

**Lab 1: Docker**
```bash
cd labs/1_ContainersAndDocker
docker build -t hello-world:1.0 .
docker run -p 8080:8080 hello-world:1.0
```

**Lab 2: Kubernetes**
```bash
cd labs/2_IntroKubernetes
kubectl apply -f hello-world-apply.yaml
```

**Lab 3: ConfigMaps**
```bash
cd labs/3_K8sScaleAndUpdate
kubectl apply -f deployment-configmap-env-var.yaml
```

---

## 📜 License

Licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

Copyright © 2020 IBM Developer Skills Network

---

<div align="center">

**Part of my journey learning container technologies and DevOps**

</div>
