# GET /api/v1/data/rabbitmq/organizations/{orgName}/clusters/{clusterName}/vhosts

**Resource:** [vhost](../resources/vhost.md)
**List RabbitMQ vhosts**
**Operation ID:** `listRabbitVHosts`

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

[RbmqVHostList](../schemas/Rbmq/RbmqVHostList.md)

