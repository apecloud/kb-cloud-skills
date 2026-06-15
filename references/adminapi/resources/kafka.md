# kafka

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/brokers` | Get all brokers in cluster | [View](../operations/getKafkaBrokers.md) |
| GET | `/admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/brokers/{brokerId}/configs` | Get all configs of a broker | [View](../operations/getKafkaBrokerConfigs.md) |
| PUT | `/admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/brokers/{brokerId}/configs` | Update broker config | [View](../operations/updateKafkaBrokerConfig.md) |
| GET | `/admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topics` | Get all topics in cluster | [View](../operations/getKafkaTopics.md) |
| POST | `/admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topics` | Create new topic | [View](../operations/createKafkaTopic.md) |
| GET | `/admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}` | Get topic Infos | [View](../operations/getKafkaTopicInfos.md) |
| DELETE | `/admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}` | Delete topic | [View](../operations/deleteKafkaTopic.md) |
| GET | `/admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}/brokers` | Get broker distributions of topic | [View](../operations/getKafkaTopicBrokers.md) |
| GET | `/admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}/partitions` | Get partition list of topic | [View](../operations/getKafkaTopicPartitions.md) |
| POST | `/admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}/partitions` | expand topic partition | [View](../operations/expandKafkaTopicPartitions.md) |
| GET | `/admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}/configs` | Get topic configuration | [View](../operations/getKafkaTopicConfig.md) |
| PUT | `/admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}/configs` | Update topic configuration | [View](../operations/setKafkaTopicConfig.md) |
| GET | `/admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}/consumer-groups` | List consumer groups of topic | [View](../operations/listKafkaTopicConsumerGroups.md) |
| GET | `/admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}/consumer-groups/{groupId}/offsets` | List consumer offsets of topic | [View](../operations/listKafkaTopicConsumerOffsets.md) |
| PUT | `/admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}/consumer-groups/{groupId}/offsets` | Reset consumer offset of topic | [View](../operations/resetKafkaTopicConsumerOffset.md) |
| GET | `/admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}/messages` | List messages from topic | [View](../operations/listKafkaTopicMessages.md) |
| POST | `/admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}/messages` | Produce message to topic | [View](../operations/produceKafkaTopicMessage.md) |
| GET | `/admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/consumer-groups` | List all consumer groups | [View](../operations/listKafkaConsumerGroups.md) |
| GET | `/admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/consumer-groups/{groupId}` | Get consumer group describe | [View](../operations/getKafkaConsumerGroupDescribe.md) |
| DELETE | `/admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/consumer-groups/{groupId}` | Delete consumer group | [View](../operations/deleteKafkaConsumerGroup.md) |
