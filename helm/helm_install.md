# Helm now has an installer script that will automatically grab the latest version of Helm and install it locally.
You can fetch that script, and then execute it locally. It's well documented so that you can read through it and understand what it is doing before you run it.
```bash
curl -fsSL -o get_helm.sh https://raw.githubusercontent.com/helm/helm/main/scripts/get-helm-3
```
```bash
chmod 700 get_helm.sh
```
```bash
./get_helm.sh
```
