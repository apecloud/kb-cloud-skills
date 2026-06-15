# GET /api/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}/consumer-groups/{groupId}/offsets

**Resource:** [kafka](../resources/kafka.md)
**List consumer offsets of topic**
**Operation ID:** `listKafkaTopicConsumerOffsets`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The name of organization |
| `clusterName` | path | string | Yes | The name of cluster |
| `topic` | path | string | Yes | The name of topic |
| `groupId` | path | string | Yes | The id of consumer group |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[TopicOffsetList](../schemas/Topic/TopicOffsetList.md)

