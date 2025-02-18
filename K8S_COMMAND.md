# kubernetes.md
### pod
```bash
kubectl get pod -A
```
### image
```bash
crictl image ls
```
```bash
kubectl --help
```
### Activate Tab
```bash
kubectl completion bash > /etc/bash_completion.d/kubectl
```
```bash
kubeadm completion bash > /etc/bash_completion.d/kubeadm
```
```bash
kubectl get pod -A -o wide -w
```
```bash
kubectl api-resources | grep ds
```
