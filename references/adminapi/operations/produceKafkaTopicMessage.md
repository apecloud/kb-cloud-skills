# POST /admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}/messages

**Resource:** [kafka](../resources/kafka.md)
**Produce message to topic**
**Operation ID:** `produceKafkaTopicMessage`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The name of organization |
| `clusterName` | path | string | Yes | The name of cluster |
| `topic` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [TopicMessageRequest](../schemas/Topic/TopicMessageRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

