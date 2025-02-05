#Podtato Head -  

Este projeto contém os manifests Kubernetes para o deploy do Podtato Head, uma aplicação baseada em microserviços que simula a montagem de um personagem. 
Cada parte do personagem (cabeça, braços, pernas, chapéu) é um serviço separado, implementado como um Deployment no Kubernetes.

Estrutura do Projeto :

Deployments: Define cada parte do Podtato Head como um pod separado.

Services: Exponha os serviços via ClusterIP e LoadBalancer para comunicação entre componentes e acesso externo.

Imagens: Utiliza imagens do GHCR (GitHub Container Registry) para os containers.
