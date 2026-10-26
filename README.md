# Myco Multirepo Lab — Kubernetes Manifests

Declarative deployment and service topology for the distributed multi-repo system.

## Topology & Relationships

This repository orchestrates microservices from sister repositories:
- Frontend user interface: [myco-multirepo-lab-frontend](https://github.com/vvkmj/myco-multirepo-lab-frontend).
- Backend API service: [myco-multirepo-lab-backend](https://github.com/vvkmj/myco-multirepo-lab-backend).

## Validation & Deployment

```bash
# Validate manifests client-side
kubectl apply --dry-run=client -f .

# Deploy to cluster
kubectl apply -f .
```
