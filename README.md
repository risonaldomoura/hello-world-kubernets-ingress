# nginx-kubernets-ingress

## Overview
nginx-kubernets-ingress is a [nginx](https://www.nginx.org/) deploy application for Kubernets and docker using kind and [ingress nginx](https://github.com/kubernetes/ingress-nginx/) as a reverse proxy and load balancer.

## Requirements

- Kind
- kubernets
- Docker

## How to build

1. Execute [`create_cluster.sh`](create_cluster.sh) running  `./create_cluster.sh`
2. Execute [`deploy.yaml`](deploy.yaml) running  `kubectl apply -f deployment.yaml`
3. Execute [`ingress.yaml`](ingress.yaml) running  `kubectl apply -f ingress.yaml`


## License

[Apache License 2.0](https://github.com/kubernetes/ingress-nginx/blob/main/LICENSE)

