# POST /admin/v1/environments/{environmentName}/loadbalancer/check

**Resource:** [loadBalancer](../resources/loadBalancer.md)
**Check if the load balancer is available**
**Operation ID:** `checkLoadBalancer`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | (reference) |
| 404 | (reference) |

