# Rabbitmq(AMQP, MQTT) ELK
Logstash has powered by rabbitmq input plugin and mqtt input plugin
Rabbitmq feed into logstash and logstash insert into elasticsearch

# RUN


```bash
docker-compose up -d 
```

# Log
open http://localhost:9200/logstash*/_search in browser


Make sure everything is running!

Thanks to https://github.com/blacktop/docker-logstash-alpine

