# GET /api/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/brokers

**Resource:** [kafka](../resources/kafka.md)
**Get all brokers in cluster**
**Operation ID:** `getKafkaBrokers`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The name of organization |
| `clusterName` | path | string | Yes | The name of cluster |

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

[BrokerList](../schemas/Broker/BrokerList.md)

