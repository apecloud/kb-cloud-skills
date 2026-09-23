# DELETE /admin/v1/environments/{environmentName}/loadbalancer/config

**Resource:** [loadBalancer](../resources/loadBalancer.md)
**Reset the environment load balancer configuration to the current provider defaults**
**Operation ID:** `resetLoadBalancerConfig`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The effective provider defaults after reset. |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[loadBalancerConfig](../schemas/loadBalancerConfig/loadBalancerConfig.md)

