# docker-alpine-jenkins

Jenkins on alpine w/pre-installed plugins focused on Kubernetes.

[![Docker Build Status](https://img.shields.io/docker/build/appsoa/docker-alpine-jenkins.svg?style=flat-square)](https://hub.docker.com/r/appsoa/docker-alpine-jenkins/) [![Twitter Follow](https://img.shields.io/twitter/follow/yomateod.svg?label=Follow&style=flat-square)](https://twitter.com/yomateod) [![Skype Contact](https://img.shields.io/badge/skype%20id-appsoa-ff69b4.svg?style=flat-square)](skype:appsoa?chat)

```bash
yomateod@proliant:/workspace/docker/docker-jenkins$ docker-compose up -d
Starting jenkins-master ...
Starting jenkins-master ... done

yomateod@proliant:/workspace/docker/docker-jenkins$ docker ps
CONTAINER ID        IMAGE                                COMMAND                  CREATED              STATUS              PORTS                                                         NAMES
5b9e5bd9c407        appsoa/docker-alpine-jenkins:1.0.0   "/bin/tini -- /usr..."   About a minute ago   Up 7 seconds        0.0.0.0:8080->8080/tcp, 0.0.0.0:50001->50001/tcp, 50000/tcp   jenkins-master
```
