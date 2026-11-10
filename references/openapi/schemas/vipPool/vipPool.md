# vipPool

VIP Pool

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `addresses` | string | Yes | IP Addresses |
| `id` | string | No | ID of VIP Pool |
| `name` | string | No | Name of VIP Pool. It is the MetalLB IPAddressPool resource name, generated as kb-<id>. |
| `poolName` | string | No | User facing name of the VIP Pool, used to select the pool when creating a cluster. It falls back to the IPAddressPool resource name. |
| `total` | integer (int64) | Yes | Total number of IP addresses |
| `used` | integer (int64) | Yes | Used number of IP addresses |
| `usedIPs` | string[] | No | Used IP addresses |
| `availableIPs` | string[] | No | Available IP address candidates, limited to 4096 per pool. IPv4 and IPv6 share the limit equally, with unused slots reassigned to the other family. Large pools return a partial list. |

