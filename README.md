# Rotten-Potatoes Kubernetes

A Kubernetes orchestration with Flask and MongoDB

## Getting Started

1. Criar um cluster:
   - Com o k3d: k3d cluster create --agents 3 --servers 3 -p "8080:30000@loadbalancer"
2. Acessar diretório "k8s" pelo prompt de comando;
3. Rodar o comando "kubectl apply -f deployment.yaml" e aguardar criação dos elementos (pods, replicasets, services...);
4. Acessar o web app rodando localmente em: localhost:8080
