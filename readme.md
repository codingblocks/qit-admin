# Building the client

```bash
docker build . -f dockerfile.www -t thejz/qit-admin-www
docker run -p 80:80 test:latest
```
