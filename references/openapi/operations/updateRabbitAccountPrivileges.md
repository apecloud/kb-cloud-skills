# PUT /api/v1/data/rabbitmq/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/privileges

**Resource:** [RabbitMQ](../resources/RabbitMQ.md)
**Update RabbitMQ account privileges**
**Operation ID:** `updateRabbitAccountPrivileges`

Update a RabbitMQ account privileges

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the Cluster |
| `accountName` | path | string | Yes | name of the Account |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [RbmqPermission](../schemas/Rbmq/RbmqPermission.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

