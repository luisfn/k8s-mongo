# Mongo Admin on Kubernetes

Mini application deployment with Kubernetes

## Dependencies

Minikube
Kubectl

## To execute

```
minikube start
kubectl apply -f .
minikube service mongodb-external-service (Link your external service to your external)
```

## Delete everything

kubectl delete deployments.apps --all --cascade
minikube stop