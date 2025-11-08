
---

### 🧾 Step 3: nginx/README.md
This describes what’s inside your NGINX subfolder:
```markdown
# NGINX Kubernetes Deployment

This folder contains Kubernetes manifests for deploying an NGINX web server.

## Files
- **nginx.yaml** — Base configuration for the NGINX pod/service.
- **nginx-deployment.yaml** — Deployment resource for scalable NGINX setup.
- **nginx-rc.yaml** — ReplicaController example (legacy format, for learning).

## Usage
```bash
kubectl apply -f nginx-deployment.yaml
kubectl get pods
kubectl port-forward deployment/nginx-deployment 8080:80
