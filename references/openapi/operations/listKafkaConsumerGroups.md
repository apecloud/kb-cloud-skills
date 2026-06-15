# GET /api/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/consumer-groups

**Resource:** [kafka](../resources/kafka.md)
**List all consumer groups**
**Operation ID:** `listKafkaConsumerGroups`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The name of organization |
| `clusterName` | path | string | Yes | The name of cluster |
| `groupId` | query | string | No | the id of consumer group |

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

[ConsumerGroupList](../schemas/Consumer/ConsumerGroupList.md)

