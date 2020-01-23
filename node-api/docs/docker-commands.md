# Instalar imagem
```
docker pull mongo
```

# Criar container
```
docker run --name mongodb -p 27017:27017 -d mongo
```

# Listar containers online
```
docker ps
```

# Listar todos os containers
```
docker ps -a (listar todos os containers)
```

# Iniciar um container existente
```
docker start mongodb
```