# TechChallengeFIAP.Orchestation
Este repositório é responsável pela orquestração dos serviços do projeto Tech Challenge FIAP, fornecendo configurações para execução em ambiente local e ambiente orquestrado.

## Tecnologias Utilizadas
- Docker
- Docker Compose
- Kubernetes

## Iniciar Projeto com Docker

### Pré-requisitos
- Docker
- Docker Compose

### Subindo a Aplicação
Na raiz do projeto execute o comando docker compose up

## Deploy da Aplicação no Kubernetes

### Pré-requisitos
- Cluster Kubertenes configurado
- Kubectl instalado e configurado
- Imagem Docker publicada

### Aplicando os manifests no cluster
kubectl apply -f k8s/

### Verificando os recursos criados
kubectl get pods
