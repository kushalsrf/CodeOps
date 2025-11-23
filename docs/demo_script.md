
# 5-Minute Interview Demo Script

## 1. Introduction
“I'll walk you through a production-grade platform engineering project covering infra automation, GitOps, observability, CI/CD, and testing.”

## 2. Repo Walkthrough
- **app/** contains FastAPI microservice, containerized via Docker.
- **infra/** contains Terraform modules for scalable cloud infra.
- **gitops/** holds ArgoCD definitions for declarative deployments.

## 3. CI/CD Pipeline
Explain automated build, test, security scan, and deployment triggers.

## 4. Autoscaling & Resilience
Show HPA and explain scaling thresholds.

## 5. Secrets & Compliance
Explain External Secrets Operator pulling secrets from AWS SSM.

## 6. Observability Stack
- Prometheus for metrics
- Loki for logs
- Grafana dashboards
- Jaeger for tracing

## 7. Closing
Highlight reproducibility, reliability, and end-to-end automation.
