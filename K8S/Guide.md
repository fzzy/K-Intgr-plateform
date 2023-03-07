Install minikube and running kubernetes v1.21.1 in master-slave mode
```
## install minikube on MAC
brew install minikube
## start Control Plane node
minikube start
minikube status
## add m02 node
minikube node add
minikube status
## add m03 node
minikube node add
minikube status
## enable metrics for dashboard
minikube addons enable metrics-server
## open dashboard and check cluster status
minikube dashboard
```