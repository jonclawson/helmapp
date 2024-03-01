# README

docker build -t user/slimapp:version .

docker push user/slimapp

helm install slimapp ./helm/slimapp   

kubectl get pods  

kubectl logs -f pod-name

kubectl describe pod-name

kubectl describe nodes | grep Taints   

kubectl describe pod pod-name  | grep Toleration

helm upgrade --install slimapp ./helm/slimapp

helm list 

helm uninstall slimapp

helm lint ./helm/slimapp