# PUT /admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}/consumer-groups/{groupId}/offsets

**Resource:** [kafka](../resources/kafka.md)
**Reset consumer offset of topic**
**Operation ID:** `resetKafkaTopicConsumerOffset`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The name of organization |
| `clusterName` | path | string | Yes | The name of cluster |
| `topic` | path | string | Yes | The name of topic |
| `groupId` | path | string | Yes | The id of consumer group |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [ResetOffsetRequest](../schemas/Reset/ResetOffsetRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Consumer offset successfully reset |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

