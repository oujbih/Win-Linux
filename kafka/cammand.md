# Listing the Topics available in Kafka:
```
kafka-topics.sh --list --bootstrap-server localhost:9092
```

# Creating Topic 
```
kafka-topics.sh --create \
    --bootstrap-server localhost:2181 \
    --replication-factor 1 \
    --partitions 1 \
    --topic GTC
    
bin/kafka-topics.sh --create  --bootstrap-server localhost:9092  --replication-factor 1  --partitions 1 --topic OUJBIH
```

# Sending data 
```
bin/kafka-console-producer.sh --topic GTC --bootstrap-server localhost:9092
First message
Second message

sudo docker exec -it broker kafka-console-producer  --topic gps --bootstrap-server localhost:9092  
```

# read the data 
```
kafka-console-consumer.sh --bootstrap-server localhost:9092 --topic GTC --from-beginning
sudo docker exec -it broker kafka-console-consumer  --topic gps --bootstrap-server localhost:9092 --from-beginning
```
