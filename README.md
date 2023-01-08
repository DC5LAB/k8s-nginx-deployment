# k8s-nginx-deployment


## Basic deployment with 2 pods
```bash
 kubectl apply -f https://raw.githubusercontent.com/DC5LAB/k8s-nginx-deployment/main/nginx-deployment.yaml
```

### Show info about deployment
```bash
 kubectl describe deployment nginx-deployment
 ```
 
 ### List pods
 ```bash
 kubectl get pods -l app=nginx
 ```
 
 ### Show info about pods
 
 ```bash
 kubectl describe pod <pod-name>
 ```
 
 ## Delete nginx deployment
 
```bash
kubectl delete deployment nginx-deployment
```
