# vipPoolCreate

VIP Pool create

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `addresses` | string | Yes | IP Addresses |
| `poolName` | string | Yes | Name of the VIP Pool. It is what a cluster selects the pool by, so it is not restricted by Kubernetes resource naming rules. The MetalLB IPAddressPool resource name stays the generated kb-<id>. |

