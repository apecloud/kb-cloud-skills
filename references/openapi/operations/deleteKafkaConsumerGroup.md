# DELETE /api/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/consumer-groups/{groupId}

**Resource:** [kafka](../resources/kafka.md)
**Delete consumer group**
**Operation ID:** `deleteKafkaConsumerGroup`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The name of organization |
| `clusterName` | path | string | Yes | The name of cluster |
| `groupId` | path | string | Yes | The id of consumer group |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Consumer group successfully deleted |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

