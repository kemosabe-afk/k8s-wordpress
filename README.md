# k8s-wordpress

### spin up wordpress with kubernetes

1. git clone https://github.com/kemosabe-afk/k8s-wordpress.git
2. kubectl apply -f nginx_configMap.yaml
3. kubectl apply -k ./

for accessing wordpress, type 'minikube service wordpress --url'
