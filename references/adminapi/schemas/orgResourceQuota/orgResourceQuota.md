# orgResourceQuota

org resource quota

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cpu` | number | Yes | Maximum available vCPU. if set to 0, no limit |
| `memory` | number | Yes | Maximum available memory in GB. if set to 0, no limit |
| `storage` | number | Yes | Maximum available storage in GB. if set to 0, no limit |
| `clusters` | object | Yes | Number of the clusters. key is engine type, values is the maximum number of engine |

