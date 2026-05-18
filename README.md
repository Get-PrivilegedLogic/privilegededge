# PrivilegedEdge

Secure Kubernetes edge platform built on Raspberry Pi 5 using K3s, AWS integrations, observability, RBAC, and GitOps workflows.

## Project Goals

This project was created to develop hands-on experience with:

- Kubernetes and container orchestration
- Cloud-native security practices
- Infrastructure automation
- Secrets management
- Observability and monitoring
- GitOps deployment workflows
- Secure platform engineering concepts

---

## Architecture

- Raspberry Pi 5
- Ubuntu Server 24.04 LTS
- K3s Kubernetes
- Traefik ingress controller
- NGINX test workload
- Prometheus + Grafana (planned)
- AWS Secrets Manager integration (planned)
- ArgoCD GitOps workflows (planned)

---

## Current Status

### Completed
- Ubuntu Server installation
- Static IP configuration
- K3s cluster deployment
- NGINX test workload deployment
- NodePort service exposure

### In Progress
- Observability stack
- RBAC implementation
- Secrets management integration

### Planned
- ArgoCD GitOps
- External Secrets
- Policy-as-Code
- Container security scanning

---

## Security Design Principles

- Least-privilege access
- RBAC segmentation
- Externalized secrets
- Infrastructure-as-Code
- Secure-by-default configurations
- Observability and auditability

---

## Future Enhancements

- AWS Secrets Manager integration
- Kubernetes NetworkPolicies
- Falco runtime security
- Trivy image scanning
- CI/CD security automation
- Multi-node Kubernetes cluster expansion
