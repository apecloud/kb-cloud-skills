# DELETE /admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}

**Resource:** [kafka](../resources/kafka.md)
**Delete topic**
**Operation ID:** `deleteKafkaTopic`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The name of organization |
| `clusterName` | path | string | Yes | The name of cluster |
| `topic` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Topic successfully deleted |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

