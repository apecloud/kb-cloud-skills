# GET /api/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}/consumer-groups

**Resource:** [kafka](../resources/kafka.md)
**List consumer groups of topic**
**Operation ID:** `listKafkaTopicConsumerGroups`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The name of organization |
| `clusterName` | path | string | Yes | The name of cluster |
| `topic` | path | string | Yes | The name of topic |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[ConsumerGroupList](../schemas/Consumer/ConsumerGroupList.md)

