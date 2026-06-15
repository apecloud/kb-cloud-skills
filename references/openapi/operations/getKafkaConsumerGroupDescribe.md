# GET /api/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/consumer-groups/{groupId}

**Resource:** [kafka](../resources/kafka.md)
**Get consumer group describe**
**Operation ID:** `getKafkaConsumerGroupDescribe`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The name of organization |
| `clusterName` | path | string | Yes | The name of cluster |
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

[ConsumerGroupDescribeResponse](../schemas/Consumer/ConsumerGroupDescribeResponse.md)

