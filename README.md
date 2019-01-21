- Tutorial: https://realpython.com/dockerizing-flask-with-compose-and-machine-from-localhost-to-the-cloud/
- Repositorio: https://github.com/realpython/orchestrating-docker
- Imagen de Nginx: https://hub.docker.com/r/tutum/nginx

1. Construir el entorno para docker-compose
```
$ docker-compose build
$ docker-compose up -d
```
Crear una base de datos (PostgreSQL):
```
$ docker-compose run web /usr/local/bin/python create_db.py
```

Acceder al servidor:
```
http://localhost:80 (o el puerto en el que hayas montado el servicio 'nginx' de docker-compose'
```

## Dockerizing Flask With Compose and Machine - From Localhost to the Cloud

Featuring:

- Docker v1.9.0
- Docker Compose v1.5.0
- Docker Machine v0.5.0

**Check out the awesome blog post here > https://realpython.com/blog/python/dockerizing-flask-with-compose-and-machine-from-localhost-to-the-cloud/**

Cheers!
