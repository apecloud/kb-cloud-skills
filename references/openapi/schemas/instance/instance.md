# instance

Instance is the information of KubeBlocks cluster instances

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `accessMode` | string | Yes | Access mode for instance |
| `orgName` | string | No | Org name |
| `cloud` | string | Yes | Cloud for instance |
| `cluster` | string | Yes | Cluster name |
| `componentName` | string | No | Component name |
| `componentDef` | string | No | ComponentDefinition name |
| `component` | string | Yes | component type, refer to componentDef and support NamePrefix |
| `cpu` | string | Yes | cpu with uint cores. |
| `createdAt` | string | Yes | created at |
| `memory` | string | Yes | Memory with uint Gi. |
| `name` | string | Yes | Instance name |
| `node` | string | Yes | node name |
| `containers` | string[] | No | Container names in the pod |
| `podIP` | string | No | Pod IP address |
| `region` | string | Yes | Region for instance |
| `role` | string | Yes | Role for instance |
| `status` | object | Yes | Status for instance |
| `storage` | instanceStorageItem[] | No | storage sets the storage size value mapping key |
| `zone` | string | Yes | Available zone for instance |

## Nested Fields

### `status`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `phase` | string | Yes | The current phase of the cluster |
| `reason` | string | No | A brief reason for the cluster's current phase |
| `message` | string | No | A human-readable message indicating details about the cluster's current phase |

