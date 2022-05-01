# k8s-wordpress

### spin up wordpress with kubernetes (minikube)

1. git clone https://github.com/kemosabe-afk/k8s-wordpress.git
2. minikube start
3. kubectl apply -f nginx_configMap.yaml
4. kubectl apply -k ./

for accessing wordpress, type 'minikube service wordpress --url'
