# GET /api/v1/data/rabbitmq/organizations/{orgName}/clusters/{clusterName}/accounts

**Resource:** [RabbitMQ](../resources/RabbitMQ.md)
**List RabbitMQ accounts**
**Operation ID:** `listRabbitAccounts`

List all RabbitMQ accounts

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

[RbmqAccountsList](../schemas/Rbmq/RbmqAccountsList.md)

