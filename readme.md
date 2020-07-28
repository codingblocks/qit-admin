# QIT Admin

## Setup

1. Install Skaffold

https://skaffold.dev/docs/install/

2. Run Skaffold

`skaffold dev`

3. Run http://localhost:80

## Requirements

- Docker
- Kubernetes

## Deploying

```bash
helm install qit-admin-www deployment/qit-admin-www
kubectl port-forward svc/qit-admin-www 8080:80
open localhost:8080
```
