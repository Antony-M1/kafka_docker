This `chatgpt.yml` file is working fine

Have to create the cluster first
```
docker network create kafka-net
```

Run the container
```
docker compose -f chatgpt.yml up -d
```

To see the logs for `zookeeper`, `kafka` & `kafka-manager`
```
docker-compose logs zookeeper
```
```
docker-compose logs kafka
```
```
docker-compose logs kafka-manager
```