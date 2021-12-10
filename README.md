# nginx-kubernets-ingress
This is a nginx deploy application with Kubernets and docker using kind and ingress service

## Requirements

1. Kind
2. kubernets
3. Docker

## How to build

1. Execute create_cluster.sh running command  `./create_cluster.sh`
2. Execute deployment.yaml running command  `kubectl apply -f deployment.yaml`
3. Execute ingress.yaml running command  `kubectl apply -f ingress.yaml`


## License

[Apache License 2.0](https://github.com/kubernetes/ingress-nginx/blob/main/LICENSE)

