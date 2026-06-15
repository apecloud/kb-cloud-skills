# GET /admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topics

**Resource:** [kafka](../resources/kafka.md)
**Get all topics in cluster**
**Operation ID:** `getKafkaTopics`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The name of organization |
| `clusterName` | path | string | Yes | The name of cluster |
| `nameFilter` | query | string | No | search pattern, support prefix search |
| `onlyNames` | query | boolean | No | if true, only return topic names |

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

[TopicsList](../schemas/Topics/TopicsList.md)

