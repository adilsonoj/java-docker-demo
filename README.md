# Docker Multi-Stage para Aplicações JAVA

## Passos para construir e rodar a imagem

1. Construir a imagem:
```shell
docker build -t minha-aplicacao:latest .
```

2. Construir a imagem:
```shell
docker run -p 8080:8080 minha-aplicacao:latest
```