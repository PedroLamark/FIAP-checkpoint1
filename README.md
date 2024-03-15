# Checkpoint 1: Criando, compilando e executando um projeto Spring no Docker

## Executando imagem
```
docker run -p 8080:8080 fiap-checkpoint1
```

## Como executar no modo DEV
```
docker run -p 8080:8080 -e PROFILE=dev fiap-checkpoint1
ou
docker run -p 8080:8080 fiap-checkpoint1
```

## Como executar no modo stg
```
docker run -p 8080:8080 -e PROFILE=stg fiap-checkpoint1
```

## Como executar no modo prd
```
docker run -p 8080:8080 -e PROFILE=prd fiap-checkpoint1
```

## Membros
RM96158 - [Pedro Lucca Lamark](https://github.com/PedroLamark)

RM95818 - [Luiz Macilia](https://github.com/LuizMacilia)