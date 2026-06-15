# kafka

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/brokers` | Get all brokers in cluster | [View](../operations/getKafkaBrokers.md) |
| GET | `/api/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/brokers/{brokerId}/configs` | Get all configs of a broker | [View](../operations/getKafkaBrokerConfigs.md) |
| PUT | `/api/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/brokers/{brokerId}/configs` | Update broker config | [View](../operations/updateKafkaBrokerConfig.md) |
| GET | `/api/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topics` | Get all topics in cluster | [View](../operations/getKafkaTopics.md) |
| POST | `/api/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topics` | Create new topic | [View](../operations/createKafkaTopic.md) |
| GET | `/api/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}` | Get topic Infos | [View](../operations/getKafkaTopicInfos.md) |
| DELETE | `/api/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}` | Delete topic | [View](../operations/deleteKafkaTopic.md) |
| GET | `/api/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}/brokers` | Get broker distributions of topic | [View](../operations/getKafkaTopicBrokers.md) |
| GET | `/api/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}/partitions` | Get partition list of topic | [View](../operations/getKafkaTopicPartitions.md) |
| POST | `/api/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}/partitions` | expand topic partition | [View](../operations/expandKafkaTopicPartitions.md) |
| GET | `/api/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}/configs` | Get topic configuration | [View](../operations/getKafkaTopicConfig.md) |
| PUT | `/api/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}/configs` | Update topic configuration | [View](../operations/setKafkaTopicConfig.md) |
| GET | `/api/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}/consumer-groups` | List consumer groups of topic | [View](../operations/listKafkaTopicConsumerGroups.md) |
| GET | `/api/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}/consumer-groups/{groupId}/offsets` | List consumer offsets of topic | [View](../operations/listKafkaTopicConsumerOffsets.md) |
| PUT | `/api/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}/consumer-groups/{groupId}/offsets` | Reset consumer offset of topic | [View](../operations/resetKafkaTopicConsumerOffset.md) |
| GET | `/api/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}/messages` | List messages from topic | [View](../operations/listKafkaTopicMessages.md) |
| POST | `/api/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}/messages` | Produce message to topic | [View](../operations/produceKafkaTopicMessage.md) |
| GET | `/api/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/consumer-groups` | List all consumer groups | [View](../operations/listKafkaConsumerGroups.md) |
| GET | `/api/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/consumer-groups/{groupId}` | Get consumer group describe | [View](../operations/getKafkaConsumerGroupDescribe.md) |
| DELETE | `/api/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/consumer-groups/{groupId}` | Delete consumer group | [View](../operations/deleteKafkaConsumerGroup.md) |
| GET | `/api/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/accounts` | List cluster accounts | [View](../operations/listKafkaAccounts.md) |
| POST | `/api/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/accounts` | Create cluster account | [View](../operations/createKafkaAccount.md) |
| DELETE | `/api/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}` | Delete cluster account | [View](../operations/deleteKafkaAccount.md) |
| PATCH | `/api/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}` | update cluster account | [View](../operations/updateKafkaAccount.md) |
