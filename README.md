# Apache Kafka

## Terminology



- Producer - An application that sends messages to Kafka. A message is a single line of data.
- Consumer - An application that reads data from Kafka.
- Broker - It is an alias for Kafka server.
- Cluster - A group of computers sharing workload for common purpose.
- Topic - A topic is a unique name for Kafka stream.
- Partitions - Part of a topic. #partitions = #kafkabrokers
- Offset - Unique id for a message within a partition. The broker stores the messages in the order of their arrival.
  To locate a particular message, you need 3 things:
  - topic name
  - partition number
  - offset
- Consumer groups - A group of consumers acting as a single logical unit.

