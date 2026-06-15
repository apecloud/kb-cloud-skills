# GET /admin/v1/data/rabbitmq/organizations/{orgName}/clusters/{clusterName}/exchanges

**Resource:** [exchange](../resources/exchange.md)
**List RabbitMQ exchanges**
**Operation ID:** `listRabbitExchanges`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the Cluster |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[RbmqExchangeList](../schemas/Rbmq/RbmqExchangeList.md)

