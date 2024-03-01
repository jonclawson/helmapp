# README

docker build -t user/helmapp:version .

docker push user/helmapp

helm install helmapp ./helm/helmapp   

kubectl get pods  

kubectl logs -f pod-name

kubectl describe pod pod-name

kubectl describe nodes | grep Taints   

kubectl describe pod pod-name  | grep Toleration

helm upgrade --install helmapp ./helm/helmapp

helm list 

helm uninstall helmapp

helm lint ./helm/helmapp