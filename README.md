Minicube Hello World!
1. Запуск minikube кластера: minikube start
2. Создание развертывания: kubectl create deployment hello-minikube --image=registry.k8s.io/echoserver:1.10
3. Создание сервиса: kubectl expose deployment hello-minikube --type=NodePort --port=8080
4. Проверка под: kubectl get pod
5. Установка порта: kubectl port-forward service/hello-minikube 8081:8080
6. Проверка под: kubectl get pod
7. Открытия url в браузере
