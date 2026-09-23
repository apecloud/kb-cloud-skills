# PUT /admin/v1/environments/{environmentName}/loadbalancer/config

**Resource:** [loadBalancer](../resources/loadBalancer.md)
**Save and immediately activate the load balancer configuration of an environment**
**Operation ID:** `updateLoadBalancerConfig`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [loadBalancerConfigUpdate](../schemas/loadBalancerConfigUpdate/loadBalancerConfigUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 400 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[loadBalancerConfig](../schemas/loadBalancerConfig/loadBalancerConfig.md)

