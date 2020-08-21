
## Prerequisites

kubectl create namespace cert-manager
kubectl apply --validate=false -f https://github.com/jetstack/cert-manager/releases/download/v0.12.0/cert-manager.yaml
kubectl get ns
kubectl get pods --namespace cert-manager
kubectl get all --namespace cert-manager
kubectl apply -f cert1.yml
kubectl get all --namespace hotel
kubectl get certificate -n hotel
kubectl describe certificate -n hotel

##pr