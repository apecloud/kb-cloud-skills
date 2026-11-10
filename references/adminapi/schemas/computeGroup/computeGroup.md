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
| `memberCount` | integer (int64) | No | Number of registered members. |
| `aliveMemberCount` | integer (int64) | No | Number of members reported online by the engine. |
| `members` | computeGroupMember[] | No |  |
| `computeGroupEnabled` | boolean | No | Whether the component is configured as a native compute group; task completion reports convergence. |
| `backendCount` | integer (int64) | No |  |
| `aliveBackendCount` | integer (int64) | No |  |
| `defaultUsers` | string[] | No |  |
| `backends` | computeGroupBackend[] | No |  |
| `allowedActions` | string[] | No |  |

