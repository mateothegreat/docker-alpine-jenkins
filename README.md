# docker-alpine-jenkins

Jenkins on alpine w/pre-installed plugins focused on Kubernetes.

```bash
yomateod@proliant:/workspace/docker/docker-jenkins$ docker-compose up -d
WARNING: Dependency conflict: an older version of the 'docker-py' package may be polluting the namespace. If you're experiencing crashes, run the following command to remedy the issue:
pip uninstall docker-py; pip uninstall docker; pip install docker
Starting jenkins-master ...
Starting jenkins-master ... done
yomateod@proliant:/workspace/docker/docker-jenkins$ docker ps
CONTAINER ID        IMAGE                                COMMAND                  CREATED              STATUS              PORTS                                                         NAMES
5b9e5bd9c407        appsoa/docker-alpine-jenkins:1.0.0   "/bin/tini -- /usr..."   About a minute ago   Up 7 seconds        0.0.0.0:8080->8080/tcp, 0.0.0.0:50001->50001/tcp, 50000/tcp   jenkins-master
```
