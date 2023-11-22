# kafka

![image](https://github.com/Antony-M1/kafka_docker/assets/96291963/ddd96dac-75f4-4a76-b1bc-544d498f256d)


Apache Kafka is a distributed event store and stream-processing platform. It is an open-source system developed by the Apache Software Foundation written in Java and Scala. The project aims to provide a unified, high-throughput, low-latency platform for handling real-time data feeds

# Docker Image Details
* [zookeeper](https://hub.docker.com/r/bitnami/zookeeper) Verified Publisher✅
* [kafka](https://hub.docker.com/r/bitnami/kafka/tags) Verified Publisher✅
* [Kafka Manager](https://hub.docker.com/r/hlebalbau/kafka-manager)

# YouTube
* [How to start an Apache Kafka broker with Docker and Docker-Compose](https://www.youtube.com/watch?v=Zq8aMrRnvQE)

# Other GitHub Repo
* [conduktor/kafka-stack-docker-compose](https://github.com/conduktor/kafka-stack-docker-compose)
  
# Get Start
### Step 1: Clone the project
```
git clone https://github.com/Antony-M1/kafka_docker.git
```

### Step 2: Up the Container
If you want to see the `logs` remove the `-d` from the below command
```
docker compose up -d
```

You will see like this in terminal
![image](https://github.com/Antony-M1/kafka_docker/assets/96291963/d1a5f923-6891-4f2b-a2c8-9dd50e9f1068)

Run this command to find the current `Process Status`
```
docker ps
```
you can see like this
![image](https://github.com/Antony-M1/kafka_docker/assets/96291963/4c81febd-269f-491f-9546-fec782c7bcde)

You can see the `zookeeper` running in the port `2181` and the `kafka` running in the port `9092`
