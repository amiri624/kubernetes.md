#  Create a New Token with Extended Validity:
## You can create a new token with a custom validity period using the kubeadm token create command.
### Command to create a new token:
```bash
sudo kubeadm token create --ttl <time> --print-join-command
```
### For example, to create a token valid for 7 days (168 hours), use the following command:
```bash
sudo kubeadm token create --ttl 168h --print-join-command
```
#### Here:
##### . 168h means 168 hours, which is equivalent to 7 days.
##### . --print-join-command prints the full command you need to run to join a node to the cluster using this token.
## Verify the Cluster with kubectl get nodes:
#### After joining the nodes with the new token, you can verify the nodes in the cluster by running:
```bash
kubectl get nodes
```
