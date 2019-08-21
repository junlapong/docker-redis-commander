- https://hub.docker.com/_/redis
- https://www.npmjs.com/package/redis-commander

## Docker Compose

```
docker-compose up -d
docker-compose up -d redis
```

### connecting via redis-cli

```
docker exec -it redis-server redis-cli

-- or --

redis-cli -h localhost -p 6379
redis-cli
```

### client command

```
127.0.0.1:6379> ping
PONG

> exit

> shutdown
```

## Docker Images

```
redis                            latest             98.2MB
rediscommander/redis-commander   latest             93.7MB
```

## Redis Commander

http://localhost:8081
