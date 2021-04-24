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
