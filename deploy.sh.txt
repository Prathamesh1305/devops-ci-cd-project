#!/bin/bash
docker pull yourdockerhub/devops-project:latest
docker stop web || true
docker rm web || true
docker run -d --name web -p 80:80 yourdockerhub/devops-project:latest
