# GET /admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/brokers/{brokerId}/configs

**Resource:** [kafka](../resources/kafka.md)
**Get all configs of a broker**
**Operation ID:** `getKafkaBrokerConfigs`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The name of organization |
| `clusterName` | path | string | Yes | The name of cluster |
| `brokerId` | path | integer | Yes | The id of broker |

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

[ConfigList](../schemas/Config/ConfigList.md)

