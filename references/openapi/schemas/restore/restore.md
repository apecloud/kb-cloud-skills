# restore

create a KubeBlocks restore API

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No | ID of the restore |
| `orgName` | string | No | organization name |
| `backupName` | string | Yes | backup name |
| `clusterName` | string | Yes | kubeBlocks cluster name |
| `componentName` | string | No | component name of cluster |
| `targetPodName` | string | No | target pod name |
| `createdAt` | string (date-time) | No |  |
| `name` | string | No | kubeBlocks restore name |
| `parameters` | object | No | restore parameters to inject env of the restore CR. |
| `restoreTime` | string | No | restore time |
| `duration` | string | No | duration of restore |
| `selectedObjects` | selectiveObjectTreeNode[] | No | selected objects to restore |
| `status` | object | No | restore status |

## Nested Fields

### `status`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `actions` | object[] | No |  |
| `completionTimestamp` | string (date-time) | No | completion time |
| `conditions` | object[] | No |  |
| `phase` | string | No | restore phase |
| `startTimestamp` | string (date-time) | No | start time |

#### `status.actions`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `message` | string | No |  |
| `name` | string | No | action name |
| `status` | string | No | action status, enum values: [Processing, Completed, Failed] |
| `backupName` | string | No |  |
| `objectKey` | string | No |  |
| `startTime` | string (date-time) | No |  |
| `endTime` | string (date-time) | No |  |

#### `status.conditions`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `message` | string | No |  |
| `reason` | string | No |  |
| `type` | string | No | conditionType |
| `observedGeneration` | integer (int64) | No |  |
| `lastTransitionTime` | string (date-time) | No |  |
| `status` | string | No |  |

