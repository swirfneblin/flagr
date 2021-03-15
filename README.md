# flagr


## Pre-req
- Create a cluster with [minikube](https://minikube.sigs.k8s.io/docs/start/)

## Quick demo

```sh
# Install with helm file
helm install flagr .

# Create a port-forward
kubectl port-forward service/flagr 8080:80

```
