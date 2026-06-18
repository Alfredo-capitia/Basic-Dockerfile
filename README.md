# basicDocker

Projeto introdutório de Docker do curso de DevOps.
Cria um container Alpine Linux que imprime uma saudação ao iniciar.

## Pré-requisitos

- Docker instalado

## Como usar

```bash
# Build da imagem
docker build -t basic-docker .

# Executar o container
docker run basic-docker
```

## Estrutura

- `Dockerfile` — Define a imagem base Alpine e o comando de inicialização

## Saída esperada

```
hello , Alfredo Capitia
```

## Project URL

https://roadmap.sh/projects/basic-dockerfile
