# computeGroup

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No |  |
| `componentName` | string | No |  |
| `managed` | boolean | No |  |
| `isDefault` | boolean | No |  |
| `phase` | string | No | Kubernetes component phase, independent of engine membership. |
| `stopped` | boolean | No |  |
| `replicas` | integer (int64) | No |  |
| `classCode` | string | No |  |
| `cpu` | number | No |  |
| `memory` | number | No |  |
| `backendCount` | integer (int64) | No |  |
| `aliveBackendCount` | integer (int64) | No |  |
| `defaultUsers` | string[] | No |  |
| `backends` | computeGroupBackend[] | No |  |
| `allowedActions` | string[] | No |  |

