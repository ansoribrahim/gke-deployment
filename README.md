
initiate terraform :
```
terraform init
terraform apply
```

run deployment :
```
kubectl apply -f notification-pod.yaml
```

check status
```
kubectl get pods -n default
```

