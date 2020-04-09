###Hervorragendes Indisches Tutorial:
https://www.youtube.com/watch?v=NjHYWEV_E_o
https://www.youtube.com/watch?v=IncG0_XSSBg

###Kafka Download:
https://kafka.apache.org/downloads

###Steps:
1. Start zookeeper ./bin/zookeeper-server-start.sh config/zookeeper.properties
2. Start kafka ./bin/kafka-server-start.sh config/server.properties
3. Create Topic ./bin/kafka-topics.sh --create --zookeeper localhost:2181 --replication-factor 1 --partitions 1 --topic Kafka_Example
4. Start ConsoleProducer ./bin/kafka-console-producer.sh --broker-lis.t localhost:9092 --topic Kafka_Example