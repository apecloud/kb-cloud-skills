# GET /admin/v1/environments/{environmentName}/loadbalancer/config

**Resource:** [loadBalancer](../resources/loadBalancer.md)
**Get the effective load balancer configuration of an environment**
**Operation ID:** `getLoadBalancerConfig`

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

[loadBalancerConfig](../schemas/loadBalancerConfig/loadBalancerConfig.md)

