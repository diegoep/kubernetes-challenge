# Virtualização - Desafio

Implante essa aplicação no seu [Minikube](https://github.com/kubernetes/minikube) e personalize a variável de ambiente para mostrar seu nome.

```
$ curl $(minikube ip)
Olá Diego!
```

## Instruções
- Faça fork desse repositório
- Construa a imagem Docker
- Escreva os arquivos yaml para um Deployment, Service, Ingress e ConfigMap
- Implante sua aplicação no Minikube
- Você deve conseguir rodar um `curl` para o IP do Minikube e recuperar a string `Olá {seunome}!`
- Commit e faça push dos seus arquivos pro Github

## Notas

Não há necessidade de fazer push da imagem docker para um registry. Você deve fazer build localmente e usar a imagem dentro do minikube. 

Você pode expor o Docker do minikube com o comando:
```shell
$ eval (minikube docker-env)
```
