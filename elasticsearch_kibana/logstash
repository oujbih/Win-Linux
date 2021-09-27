# conf.d
```
input {
  kafka{
    codec => json
    bootstrap_servers => "localhost:9092"
    topics => ["trading"]
  }
}



output {
  elasticsearch {
      hosts => ["localhost:9200"]
      index => "trading"
      workers => 1
  }
}
```
