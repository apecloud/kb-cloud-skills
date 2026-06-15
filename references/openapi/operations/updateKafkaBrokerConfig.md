# PUT /api/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/brokers/{brokerId}/configs

**Resource:** [kafka](../resources/kafka.md)
**Update broker config**
**Operation ID:** `updateKafkaBrokerConfig`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The name of organization |
| `clusterName` | path | string | Yes | The name of cluster |
| `brokerId` | path | integer | Yes | The id of broker |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [UpdateBrokerConfigRequest](../schemas/Update/UpdateBrokerConfigRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

