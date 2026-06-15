# GET /admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}

**Resource:** [kafka](../resources/kafka.md)
**Get topic Infos**
**Operation ID:** `getKafkaTopicInfos`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The name of organization |
| `clusterName` | path | string | Yes | The name of cluster |
| `topic` | path | string | Yes |  |

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

[TopicDetails](../schemas/Topic/TopicDetails.md)

