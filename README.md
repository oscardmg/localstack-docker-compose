```
docker-compose up --build
```

Se puede consultar http://localhost:4566/health


```
awslocal sqs list-queues
```

```
awslocal sqs create-queue --queue-name test-queue
```

# conectando directamente a docker

```
docker ps
```

```
docker exec -it id_container /bin/bash
```