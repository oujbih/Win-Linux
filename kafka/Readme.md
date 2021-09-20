

# Part 3 - Install Kafka server and zookeeper | Kafka for beginners
```
- advertised.listeners=PLAINTEXT://[server-ip-address]:9092
- zookeeper.connect=localhost:2181 
**c**
Then we will use the below command to start the server



Start zookeeper using : 
bin/zookeeper-server-start.sh config/zookeeper.properties

Start Kafka using : 
JMX_PORT=8004 bin/kafka-server-start.sh config/server.properties 


```
# Part 4
```


cd /home/gtc/.sbt/1.0/staging/9fe122a9540185ff93da/cmak/target/universal/cmak-3.0.0.5


bin/cmak -Dconfig.file=conf/application.conf -Dhttp.port=8080

```

