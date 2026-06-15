# loadBalancer

The load balancer info

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `version` | string | No | Version of the load balancer |
| `type` | string | No | Type of the load balancer |
| `status` | [loadBalancerStatus](loadBalancerStatus.md) | Yes |  |
| `available` | [loadBalancerAvailableType](loadBalancerAvailableType.md) | No |  |
| `class` | string | No | Class of the load balancer, only available on public cloud. |
| `chargeType` | string | No | Charge type of the load balancer, only available on public cloud. |
| `ipam` | [loadBalancerIpamStatus](loadBalancerIpamStatus.md) | No |  |

