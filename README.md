# nginx-kubernetes-ingress

## Overview
nginx-kubernetes-ingress is a [nginx](https://www.nginx.org/) deploy application for Kubernetes and docker using kind and [ingress nginx](https://github.com/kubernetes/ingress-nginx/) as a reverse proxy and load balancer.

## Requirements

- Kind
- kubernetes
- Docker

## How to build

1. Create a [cluster](https://kubernetes.io/pt-br/docs/concepts/overview/components/) using [`create_cluster.sh`](create_cluster.sh) running  `./create_cluster.sh`
2. Create a [deployment](https://kubernetes.io/docs/concepts/workloads/controllers/deployment/) using [`deployment.yaml`](deployment.yaml) running  `kubectl create -f deployment.yaml`
3. Create a [ingress](https://kubernetes.io/docs/concepts/services-networking/ingress/) using [`ingress.yaml`](ingress.yaml) running  `kubectl create -f ingress.yaml`

## License

[Apache License 2.0](https://github.com/kubernetes/ingress-nginx/blob/main/LICENSE)

