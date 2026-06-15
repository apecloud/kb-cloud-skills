# GET /admin/v1/environments/{environmentName}/loadbalancer

**Resource:** [loadBalancer](../resources/loadBalancer.md)
**Get the load balancer info in the environment**
**Operation ID:** `getLoadBalancer`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[loadBalancer](../schemas/loadBalancer/loadBalancer.md)

