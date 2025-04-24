# 👋 Hi, I’m Oluwadamilola Oyaluade

I'm building public infrastructure & ML projects to demonstrate senior-level cloud, DevOps, and ML engineering capability.
# 🏥 Cloud Infra Bootstrapping for Healthcare Startup

This repo sets up secure AWS cloud infrastructure for a healthcare-focused SaaS product.
We will build everything using Terraform — from IAM to EKS to ML model deployment.

---

## 🧠 Enterprise Scenario: *CareMesh Health*

**CareMesh Health** is a rapidly growing healthcare SaaS startup serving clinics and telehealth providers. They’re expanding from a single-region, single-account AWS setup into a secure, scalable, and regulated multi-account environment.

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


## 🚀 Featured Projects



| Focus Area                                 | Description                                                                                                               |
| ------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------- |
| [AWS CLI setup, IAM policies, Org structure](https://github.com/OOyaluade/cloud-infra-bootstrapping) | GitHub repo + video on secure multi-account design                                                                            |
| Modular VPC with Terraform                 | Terraform module with public/private subnets + NAT                                                                            |
| S3 with versioning, KMS, access policies   | Terraform config + explainer diagram                                                                                          |
| RDS MySQL in private subnets               | DB subnet groups, parameter tuning, secure access                                                                             |
| CI/CD pipeline with GitHub Actions         | Flask app → test → build → deploy to staging                                                                                  |
| Flask Dockerized + deployed on EC2         | Dockerfile, nginx config, systemd or ECS deploy                                                                               |
| Observability via CloudWatch/Grafana       | Alarms, dashboards, Slack alerts, JSON config                                                                                 |
| Encryption + S3 lifecycle policies         | Cost optimization + secure archiving                                                                                          |
| Centralized logging with CloudTrail + logs | Stream logs from multiple services into S3/OpenSearch                                                                         |
| Incident Response Playbook                 | Markdown runbook: rollback, alerting, escalation                                                                              |
| EKS Cluster with Terraform                 | Infra module + node group separation + OIDC                                                                                   |
| App Deployment on EKS                      | YAML or Helm charts, Ingress + TLS (cert-manager)                                                                             |
| Monitoring Kubernetes                      | Prometheus + Grafana dashboards for pods and nodes                                                                            |
| K8s Zero-Downtime Deployment               | HPA, rolling updates, canary deploy, pod disruption budgets                                                                   |
| Model Training + Tracking                  | Train a scikit-learn model (e.g. fraud detection) and log experiments with MLflow or SageMaker Experiments. Save model to S3. |
| Model Deployment on EKS                    | Containerize model with FastAPI or Flask, deploy via Helm chart to EKS. Secure with IAM + HTTPS Ingress.                      |
| CI/CD for ML Model                         | GitHub Actions to retrain, build Docker image, push to ECR, deploy to EKS. Include rollback logic.                            |
| Model Monitoring & Drift Detection         | Prometheus/Grafana for inference latency and error rate. Simulate data drift + trigger alerts or retraining job.              |
