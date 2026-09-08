# Kubernetes + Istio Canary Deployment CI/CD

A hands-on DevOps project demonstrating:

- Docker containerization
- Kubernetes deployment
- Istio service mesh
- Canary deployment
- GitHub Actions CI/CD
- Self-hosted GitHub Actions runner
- Docker Hub

## Architecture

GitHub
   ↓
GitHub Actions
   ↓
Self-hosted Runner
   ↓
Docker Build
   ↓
Docker Hub
   ↓
Kubernetes / Minikube
   ↓
Istio
   ↓
v1 / v2

## Canary Deployment

Version 1 → 90%
Version 2 → 10%

Istio VirtualService controls the traffic distribution.

## Technologies

Docker
Kubernetes
Minikube
Istio
GitHub Actions
Docker Hub
Ubuntu/Linux
