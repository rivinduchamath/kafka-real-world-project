# Please follow the below steps before work with Kafka message streams

1. Please refer below Kafka documentation to install and setup Kafka on your machine. https://kafka.apache.org/quickstart
2. Please run the below command in the terminal to start zookeeper. `bin/zookeeper-server-start.sh config/zookeeper.properties`
2. Please run the below command in the terminal to start kafka server. `bin/kafka-server-start.sh config/server.properties`
3. Please run the below command in the terminal to work with multiple instances re-balancing feature with kafka.
   `bin/kafka-topics.sh --bootstrap-server <host>:<port> --alter --partitions <no-of-partitions-defined-in-property-file> --topic <topic-name>`
