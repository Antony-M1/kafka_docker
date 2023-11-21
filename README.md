# kafka

![image](https://github.com/Antony-M1/kafka_docker/assets/96291963/ddd96dac-75f4-4a76-b1bc-544d498f256d)


Apache Kafka is a distributed event store and stream-processing platform. It is an open-source system developed by the Apache Software Foundation written in Java and Scala. The project aims to provide a unified, high-throughput, low-latency platform for handling real-time data feeds

# Docker Image Details
* [zookeeper](https://hub.docker.com/r/bitnami/zookeeper) Verified Publisher <path d="m23 12-2.44-2.79.34-3.69-3.61-.82-1.89-3.2L12 2.96 8.6 1.5 6.71 4.69 3.1 5.5l.34 3.7L1 12l2.44 2.79-.34 3.7 3.61.82L8.6 22.5l3.4-1.47 3.4 1.46 1.89-3.19 3.61-.82-.34-3.69L23 12zm-12.91 4.72-3.8-3.81 1.48-1.48 2.32 2.33 5.85-5.87 1.48 1.48-7.33 7.35z"></path>

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
