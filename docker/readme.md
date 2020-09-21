```sh
Usage:  docker pull [OPTIONS] NAME[:TAG|@DIGEST]


docker pull node
docker pull node:latest
docker pull node:12.18.3-alpine3.11
docker pull mysql:5.7.31
docker pull redis



```

```sh
docker run [OPTIONS] IMAGE [COMMAND] [ARG...]

docker run -i -t ubuntu:latest /bin/bash
docker run -i -t alpine:3.11 /bin/sh
docker run -d -p 8080:80 nginx #-d daemon -p expõe a porta 80 para a 8080 do localhost
docker run --rm -d -p 8080:80 nginx # Deleta o container logo que ele é terminado


Override no entrypoint
docker run -it --entrypoint /bin/sh alpine:3.11

```
