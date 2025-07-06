```kubectl apply -f mysql-pvc.yaml 
kubectl apply -f mysql-deployment.yaml
kubectl apply -f mysql-service.yaml

kubectl get pods -l app=mysql
kubectl port-forward <YOUR MYSQL POD NAME> 3306:3306
```