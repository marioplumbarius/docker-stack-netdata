# docker-netdata
Dockerized netdata.

**pre-requisites**
- docker (17.03.1-ce)

## usage

### enable swarm mode
```shell
docker swarm init
```

### deploy
```shell
docker stack deploy -c docker-stack.yml netdata
```

### update
```shell
docker stack deploy -c docker-stack.yml netdata
```
