# Listing the Topics available in Kafka:
```
kafka-topics.sh --list --zookeeper localhost:2181
```

# Creating Topic 
```
kafka-topics.sh --create \
    --zookeeper localhost:2181 \
    --replication-factor 1 \
    --partitions 1 \
    --topic GTC
```

# Sending data 
```
kafka-console-producer.sh --broker-list localhost:9092 --topic GTC
First message
Second message

```

# read the data 
```
kafka-console-consumer.sh --bootstrap-server localhost:9092 --topic GTC --from-beginning
```
