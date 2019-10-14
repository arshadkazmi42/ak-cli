### Create a new topic in Kafka

`kafka-topics --create --zookeeper {{ZOOKEEPER_URL}} --replication-factor {{REPLICATION_FACTOR}} --partitions {{PARTITIONS}} --topic {{TOPIC_NAME}}`

- <b>ZOOKEEPER_URL</b>: Zookeeper URL or IP:PORT
- <b>REPLICATION_FACTOR</b>: Internal topic creation will fail until the cluster size meets this replication factor requirement.
- <b>PARTITIONS</b>: Each partition is an ordered, immutable sequence of records that is continually appended to—a structured commit log.

#### Example

`kafka-topics --create   --zookeeper localhost:2181   --replication-factor 1 --partitions 1   --topic test_raw`
