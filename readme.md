# 👋 Hi, I’m Oluwadamilola Oyaluade

I'm building **Cloud Infrastructure** and **ML Systems** to demonstrate senior-level **Cloud, DevOps, and ML engineering** expertise.
## 📺 Learn Along with Me

Each module will come with:
- 🧑‍💻 **Code & Terraform**
- 📽️ **Architecture walkthrough video**
- 🖼️ **Infrastructure diagrams**
- 📄 **Obsidian-friendly documentation**
- 🔗 Shared across [GitHub](https://github.com/OOyaluade), [LinkedIn](https://www.linkedin.com/in/oluwadamilolaoyaluade), [YouTube](#), and [Twitter](#)


-------
----


> [!NOTE] **Step by Step**  
> These projects are all centered around a fictitious health care company called `CareMersh Health` with thousands of users, employees, and stakeholders  
> The goal is to simulate real-world cloud architecture while demonstrating expertise in scalable and complying infrastructure.

---

# Getting Started
## 🏥 Cloud Infra Bootstrapping for Healthcare Startup

This repository is the landing site. Links to provisioning secure and scalable AWS infrastructure using Terraform in a sequential manner are found in the table bellow.  
These links bootstraps everything from IAM to VPC networking to EKS; E.T.C — powering a regulated, fast-moving healthcare SaaS.

---
---
---

## 🧠 Enterprise Scenario: *CareMesh Health*

**CareMesh Health** is expanding from a monolithic, single-account AWS setup into a secure multi-account, multi-region architecture.  
Their product suite includes telehealth apps, predictive analytics tools, and AI-powered services — all of which must run on scalable, compliant infrastructure.

### 👩‍⚕️ Core Business Needs:
- HIPAA-compliant data storage & processing
- CI/CD pipelines for rapid deployment of patient-facing web apps and ML services
- A scalable architecture to support predictive analytics (e.g., patient no-shows, risk scoring)
- Team-based access separation: Dev, ML, Security, Compliance, and Production
- Cost transparency and control across business units

### 🌐 Cloud Infrastructure Goals:
1. **Multi-Account AWS Org** to isolate environments
2. **Terraform Modules** for repeatable networking and services
3. **EKS for App & ML Workloads** with GitHub Actions CI/CD
4. **Centralized Logging & Monitoring** for operations and incident response
5. **S3 + RDS + DynamoDB** as core data services
6. **MLflow + FastAPI + Prometheus/Grafana** stack for machine learning operations
7. **KMS, IAM SCPs, and GuardDuty** for security

## 🔧 [Cloud Infrastructure Bootstrapping](https://github.com/OOyaluade/cloud-infra-bootstrapping)


### *CareMesh Health* Progress & Roadmap

| Status         | Task                                                                   |
| -------------- | ---------------------------------------------------------------------- |
| ✅ Completed    | Modular VPC Layout created with public/private subnets, and IGW        |
| ✅ Completed    | Terraform Backend Setup with S3 state & DynamoDB lock                  |
| ✅ Completed    | S3 Bucket Module for versioned, encrypted storage                      |
| 🚧 In Progress | IAM Policies & SCPs for access separation (Dev, ML, Prod, Audit)       |
| 🚧 In Progress | Terraform Documentation & CLI Bootstrap Guide (continuous improvement) |
| 🔜 Upcoming    | Multi-Account AWS Organization setup                                   |
| 🔜 Upcoming    | Secure Networking for app and data layers                              |
| 🔜 Upcoming    | RDS Deployment with private subnet access & secrets handling           |
| 🔜 Upcoming    | EKS Cluster Provisioning with Terraform + OIDC support                 |
| 🔜 Upcoming    | CI/CD Pipelines via GitHub Actions (for apps & ML models)              |
| 🔜 Upcoming    | ML Workflow Setup with MLflow + FastAPI model serving                  |
| 🔜 Upcoming    | Observability Stack: CloudWatch, Prometheus, Grafana, and alerting     |
| 🔜 Upcoming    | Zero-Downtime Deployments using Kubernetes deployment strategies       |
| 🔜 Upcoming    | Model Monitoring & Drift Detection in production environments          |
## 🚀 Featured Projects



| Focus Area                                                                            | Description                                                                                                                   |
| ------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| [`Cloud-infra-bootstrapping`](https://github.com/OOyaluade/cloud-infra-bootstrapping) | Core infra: AWS org, VPC, IAM, state backend, foundational Terraform modules                                                  |
| Modular VPC with Terraform                                                            | Terraform module with public/private subnets + NAT                                                                            |
| S3 with versioning, KMS, access policies                                              | Terraform config + explainer diagram                                                                                          |
| RDS MySQL in private subnets                                                          | DB subnet groups, parameter tuning, secure access                                                                             |
| CI/CD pipeline with GitHub Actions                                                    | Flask app → test → build → deploy to staging                                                                                  |
| Flask Dockerized + deployed on EC2                                                    | Dockerfile, nginx config, systemd or ECS deploy                                                                               |
| Observability via CloudWatch/Grafana                                                  | Alarms, dashboards, Slack alerts, JSON config                                                                                 |
| Encryption + S3 lifecycle policies                                                    | Cost optimization + secure archiving                                                                                          |
| Centralized logging with CloudTrail + logs                                            | Stream logs from multiple services into S3/OpenSearch                                                                         |
| Incident Response Playbook                                                            | Markdown runbook: rollback, alerting, escalation                                                                              |
| EKS Cluster with Terraform                                                            | Infra module + node group separation + OIDC                                                                                   |
| App Deployment on EKS                                                                 | YAML or Helm charts, Ingress + TLS (cert-manager)                                                                             |
| Monitoring Kubernetes                                                                 | Prometheus + Grafana dashboards for pods and nodes                                                                            |
| K8s Zero-Downtime Deployment                                                          | HPA, rolling updates, canary deploy, pod disruption budgets                                                                   |
| Model Training + Tracking                                                             | Train a scikit-learn model (e.g. fraud detection) and log experiments with MLflow or SageMaker Experiments. Save model to S3. |
| Model Deployment on EKS                                                               | Containerize model with FastAPI or Flask, deploy via Helm chart to EKS. Secure with IAM + HTTPS Ingress.                      |
| CI/CD for ML Model                                                                    | GitHub Actions to retrain, build Docker image, push to ECR, deploy to EKS. Include rollback logic.                            |
| Model Monitoring & Drift Detection                                                    | Prometheus/Grafana for inference latency and error rate. Simulate data drift + trigger alerts or retraining job.              |
