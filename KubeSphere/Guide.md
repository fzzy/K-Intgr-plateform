Install KubeSphere
```
## add helm repo
helm repo add kubesphere-test https://charts.kubesphere.io/test
## install kubesphere
helm install kubesphere ks-installer --namespace=kubesphere-system --create-namespace
```

···
kubectl apply -f https://github.com/kubesphere/ks-installer/releases/download/v3.3.1/kubesphere-installer.yaml


kubectl apply -f https://github.com/kubesphere/ks-installer/releases/download/v3.3.1/cluster-configuration.yaml

···