# nelsone-k8
    
Deploy K8 Dashboard:
```shell
kubectl apply -f https://raw.githubusercontent.com/kubernetes/dashboard/v1.10.1/src/deploy/recommended/kubernetes-dashboard.yaml
```

View the dashboard:
```shell
kubectl proxy --port=8080 --address='0.0.0.0' --disable-filter=true &
```

## some thing to do locally

Setup Helm
```shell
curl -sSL https://raw.githubusercontent.com/helm/helm/master/scripts/get-helm-3 | bash
```
