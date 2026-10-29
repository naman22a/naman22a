# 👨‍💻 Full-Stack & Systems Developer | Distributed Systems Builder

Hi, I'm **Naman Arora** 👋

I enjoy building **scalable backend systems, developer tools, and cloud-native applications**.

Most of my work revolves around **distributed systems, container orchestration, and developer infrastructure**.

🚀 Current interests

- 🧩 Designing **microservices architectures**
- ☸️ Building systems on **Kubernetes**
- 🐧 Working deeply with **Linux & containerized environments**
- 🤖 Building **AI-powered developer tools**
- ⚡ Improving **system reliability and observability**

---

# 🛠️ Technical Stack

### 💻 Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

### 🌐 Web & Backend

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)

---

### 🗄️ Databases & Queues

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-D82C20?style=for-the-badge&logo=redis&logoColor=white)

---

### ☁️ DevOps & Cloud

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)

---

### 📊 Observability

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Loki](https://img.shields.io/badge/Loki-000000?style=for-the-badge&logo=grafana&logoColor=white)

---

# 🏗️ Featured Projects

## 👨‍⚖️ Online Judge Platform

<img src="https://raw.githubusercontent.com/naman22a/online-judge-platform/refs/heads/master/assets/architecture.png" alt="Architecture Diagram" height="150" width="300" />

🔗 https://github.com/naman22a/online-judge-platform

A **scalable LeetCode-style Online Judge** built using a **distributed microservices architecture**.

**Tech Stack**

React • TypeScript • NestJS • PostgreSQL • Redis • Docker • Kubernetes • BullMQ

**Key highlights**

- Designed a **7-service microservices architecture** behind an API Gateway.
- Built a **secure code execution engine using Kubernetes Jobs** to run untrusted code in isolated containers.
- Implemented **asynchronous submission processing using Redis + BullMQ workers**.
- Sustained **500 concurrent virtual users** and **2,800+ requests/sec** during k6 load testing with **P95 latency of 206 ms**.
- Added reliability mechanisms including **idempotent APIs, retry-safe execution, and dead-letter queues**.

---

## ☸️ KubeSage: AI Kubernetes Debugging CLI

🔗 https://github.com/naman22a/kubesage

An **AI-powered Kubernetes debugging CLI** that analyzes cluster diagnostics and identifies root causes automatically.

**Tech Stack**

Python • Kubernetes • AWS • LLM APIs • CLI

**Key highlights**

- Built an AI-powered CLI that analyzes Kubernetes pod logs, events and metrics to identify failures such as **CrashLoopBackOff** and **OOMKilled**.
- Integrated **Amazon Bedrock** with **CloudWatch and DynamoDB** for root-cause analysis, **SNS** alerting and incident knowledge management

---

## 🔵🟢 AWS Blue-Green Deployment

<img src="https://raw.githubusercontent.com/naman22a/blue-green-deployment-on-aws/master/docs/images/01-architecture.png" alt="Architecture Diagram" height="150" width="300" />

🔗 https://github.com/naman22a/blue-green-deployment-on-aws

Zero-downtime deployments for an NGINX app on Amazon ECS, fully automated with Terraform and GitHub Actions. Push to master, and the new version is built, deployed alongside the old one, health-checked, and only then given live traffic. If validation fails, traffic never moves.

**Tech Stack**

Terraform • AWS ECS Fargate • Github Actions • ECR

**Key highlights**

- Provisioned 10+ AWS infrastructure resource configurations using **Terraform**, deploying dual **ECS Fargate** environments behind an **Application Load Balancer** for blue-green releases.
- Automated the CI/CD pipeline with GitHub Actions and **AWS OIDC**, building and publishing Docker images to **ECR**, then deploying and smoke-testing releases before switching live traffic.
- Implemented pre-cutover health validation, ECS deployment **circuit-breaker rollback**, manual production approval, and a rollback workflow; configured **3 CloudWatch alarms** for ALB 5xx errors and unhealthy targets.

---

# 📬 Connect With Me

<div align="center">

<a href="https://www.linkedin.com/in/naman22a">
<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="https://github.com/naman22a">
<img src="https://img.shields.io/badge/github-181717.svg?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<a href="mailto:namanarora1022@gmail.com">
<img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<a href="https://namanarora.xyz">
<img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge"/>
</a>

</div>

---

⭐ _I enjoy building systems that are reliable, scalable, and developer-friendly._
