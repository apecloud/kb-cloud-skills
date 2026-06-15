# DELETE /api/v1/data/rabbitmq/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}

**Resource:** [RabbitMQ](../resources/RabbitMQ.md)
**Delete RabbitMQ account**
**Operation ID:** `deleteRabbitAccount`

Delete a RabbitMQ account

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the Cluster |
| `accountName` | path | string | Yes | name of the Account |

## Responses

| Status | Description |
|--------|-------------|
| 204 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

