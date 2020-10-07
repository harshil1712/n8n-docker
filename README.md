## n8n - Ubuntu Docker Image

Dockerfile to build n8n with Ubuntu.

[![Run on Google Cloud](https://deploy.cloud.run/button.svg)](https://deploy.cloud.run?git_repo=https://github.com/harshil1712/n8n-docker)

For information about how to run n8n with Docker check the generic
[Docker-Readme](https://github.com/n8n-io/n8n/tree/master/docker/images/n8n/README.md)


```
docker build --build-arg N8N_VERSION=<VERSION> -t n8nio/n8n:<VERSION> .

# For example:
docker build --build-arg N8N_VERSION=0.43.0 -t n8nio/n8n:0.43.0-ubuntu .
```

```
docker run -it --rm \
  --name n8n \
  -p 5678:5678 \
  n8nio/n8n:0.43.0-ubuntu
```
