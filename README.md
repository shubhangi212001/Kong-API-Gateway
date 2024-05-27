# Kong-API-Gateway
k8s based kong api gateway setup with konga user interface and postgresql database

kubectl apply -f configmap.yaml

kubectl apply -f postgresql-deployment.yaml

kubectl apply -f postgresql-service.yaml

kubectl apply -f temporary-kong-pod.yaml

kubectl apply -f kong-deployment.yaml

kubectl apply -f kong-service.yaml

kubectl apply -f konga-deployment.yaml

kubectl apply -f konga-service.yaml
