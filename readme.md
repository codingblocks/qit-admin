# Building the client

```bash
docker build . -f dockerfile.www -t test
docker run -p 80:80 test:latest
```
