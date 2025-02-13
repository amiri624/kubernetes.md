# Using Pods 
### The following is an example of a Pod which consists of a container running 
### the image nginx:1.14.2. 
##### pods/simple-pod.yaml
```bash
apiVersion: v1
kind: Pod
metadata:
  name: nginx
spec:
  containers:
  - name: nginx
    image: nginx:1.14.2
    ports:
    - containerPort: 80
```
