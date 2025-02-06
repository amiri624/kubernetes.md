# Installation and usage 
```bash
kind create cluster
```
### To delete your cluster use:
```bash
kind delete cluster
```
### To create a cluster from Kubernetes source:

### . ensure that Kubernetes is cloned in $(go env GOPATH)/src/k8s.io/kubernetes
### . build a node image and create a cluster with
```bash
kind build node-image
kind create cluster --image kindest/node:latest
```
