# Apache Druid for Kubernetes

This repo contains the code to run Druid in your Kubernetes cluster. Written in FluxCD systree.

Druid was deployed using Docker Compose ([official documentation](https://druid.apache.org/docs/latest/tutorials/docker.html)) and translated to Kubernetes Resources with [Kompose](https://kubernetes.io/docs/tasks/configure-pod-container/translate-compose-kubernetes/).

Fixed issue about failure of creating directories ([#11166](https://github.com/apache/druid/issues/11166)).
