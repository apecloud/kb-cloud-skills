# PUT /api/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}/configs

**Resource:** [kafka](../resources/kafka.md)
**Update topic configuration**
**Operation ID:** `setKafkaTopicConfig`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The name of organization |
| `clusterName` | path | string | Yes | The name of cluster |
| `topic` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [UpdateTopicConfigRequest](../schemas/Update/UpdateTopicConfigRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

