# PATCH /admin/v1/data/rabbitmq/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}

**Resource:** [RabbitMQ](../resources/RabbitMQ.md)
**Update RabbitMQ account password**
**Operation ID:** `updateRabbitAccountPassword`

Update a RabbitMQ account password

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the Cluster |
| `accountName` | path | string | Yes | name of the Account |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [RbmqUser](../schemas/Rbmq/RbmqUser.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

