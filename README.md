# Kubernetes Projects

This repository contains various Kubernetes configuration files and manifests for deploying and managing containerized applications on a Kubernetes cluster.

## 📁 Repository Structure

kubernetes-projects/

 ├── nginx/ # NGINX deployment examples
 │ ├── nginx.yaml
 │ ├── nginx-deployment.yaml
 │ ├── nginx-rc.yaml
 │ └── README.md
 └── docs/ # Optional documentation

 
## 🚀 Getting Started

### Prerequisites
- A running Kubernetes cluster (e.g., Minikube, Docker Desktop, or EKS)
- `kubectl` CLI installed and configured

### Deploy Example (NGINX)
```bash
kubectl apply -f nginx/nginx-deployment.yaml
kubectl get pods
kubectl get svc

## Clean up

kubectl delete -f nginx/

