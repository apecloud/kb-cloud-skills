# opsExpose

OpsExpose is the payload to expose a KubeBlocks cluster

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `component` | string | Yes |  |
| `enable` | boolean | Yes |  |
| `readonly` | boolean | No |  |
| `type` | [opsExposeType](opsExposeType.md) | Yes |  |
| `vpcServiceType` | [opsExposeVPCServiceType](opsExposeVPCServiceType.md) | No |  |
| `portsMapping` | object[] | No |  |
| `loadBalancerIP` | string | No | The requested IPv4 or IPv6 address of the LoadBalancer service. If not set, IP addresses will be assigned by the system. For dual-stack MetalLB services, the system allocates the missing address family from the same VIP pool. Only available when vpcServiceType is LoadBalancer. |
| `loadBalancerIPPoolID` | string | No | The IP pool ID of the LoadBalancer service. If not set, the IP pool will be assigned by the system. All VIPs of a dual-stack MetalLB service are allocated from the same pool. Only available when vpcServiceType is LoadBalancer. |
| `domain` | string | No | The custom domain for accessing the cluster. If not set, the default domain will be used. Max 253 characters in total (1-63 characters per segment), allowing only lowercase letters, numbers, and hyphens (-); each segment must start and end with a letter or number. |

## Nested Fields

### `portsMapping`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `old` | integer | No |  |
| `new` | integer | No |  |

