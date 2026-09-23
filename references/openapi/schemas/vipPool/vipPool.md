# vipPool

VIP Pool

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `addresses` | string | Yes | IP Addresses |
| `id` | string | No | ID of VIP Pool |
| `total` | integer (int64) | Yes | Total number of IP addresses |
| `used` | integer (int64) | Yes | Used number of IP addresses |
| `usedIPs` | string[] | No | Used IP addresses |
| `availableIPs` | string[] | No | Available IP address candidates, limited to 4096 per pool. IPv4 and IPv6 share the limit equally, with unused slots reassigned to the other family. Large pools return a partial list. |

