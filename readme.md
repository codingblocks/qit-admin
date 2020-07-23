# Deploying

```bash
helm install qit-admin-www deployment/qit-admin-www
kubectl port-forward svc/qit-admin-www 8080:80
open localhost:8080
```
