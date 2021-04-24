# FASTAPI DOCKER

```
python3 -m venv venv
```

```
. venv/bin/activate
```

```
pip freeze > requirements.txt
```

```
docker build -t python-fastapi .
```

```
docker run -p 8000:8000 python-fastapi
```

- Visualizar processos em execução:

```
docker ps
```

- Executar terminal dentro do container:

```
docker exec -it IDPROCESSO /bin/sh
```

[Referência](https://medium.com/xebia-engineering/learning-docker-by-building-a-python-application-e81f1486d067#)

### Adicionar ao Docker Hub

- Adicionar tag

```
docker tag python-fastapi dmalberto/python-fastapi

```

- Push para o server

```
docker push dmalberto/python-fastapi
```

[Referência](https://jtemporal.com/subindo-imagens-docker-pro-dockerhub/)
