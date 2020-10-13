RabbitMQ 3.8 with consul service discovery

### Build docker image
```
docker build --tag astvision/rabbitmq:latest .
```

### Push docker image
```
docker push astvision/rabbitmq-3.8:latest
```

### Push tags to maintain image on docker hub
```
git tag -a "$version" -m "version $version"
git push --tags
```
