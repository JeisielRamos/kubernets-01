# Studing Kubernets - Basic level

Study on the DIO platform 

- List pods
```
 kubectl get pods
```

- Get pods details
```
 kubectl get pod -o wide
```

- deleted pod
```
 kubectl deleted pod name-pod
```

- Up yml file
```
 kubectl apply -f nameFile.yml
```

- Scale deployments
```
kubectl scale deployment app-html-deployment --replicas=10
```

- Get nodes
```
 kubectl get nodes
```

- Details nodes
```
  kubectl describe node name-node
```

- Expose deployment with loadbalance
```
kubectl expose deployment app-html-deployment --type=LoadBalancer --name=app-html --port=80
```