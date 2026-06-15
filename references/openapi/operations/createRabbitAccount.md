# POST /api/v1/data/rabbitmq/organizations/{orgName}/clusters/{clusterName}/accounts

**Resource:** [RabbitMQ](../resources/RabbitMQ.md)
**Create RabbitMQ account**
**Operation ID:** `createRabbitAccount`

Create a new RabbitMQ account

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the Cluster |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [RbmqAccountRequest](../schemas/Rbmq/RbmqAccountRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

