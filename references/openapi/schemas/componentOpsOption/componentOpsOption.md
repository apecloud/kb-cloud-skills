# componentOpsOption

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `modes` | string[] | No | List of modes that this component supports. if not set, support all modes. |
| `component` | string | Yes |  |
| `disableHA` | boolean | No |  |
| `inPlace` | boolean | No | parameter for rebuild instance ops |
| `needBackupWhenInPlace` | boolean | No | indicate whether backup is required when Inplace is true |
| `backupRequired` | boolean | No | indicate whether backup is required for this ops |
| `backupMethod` | object | No | indicate the backup method when inplace is true |
| `restoreEnv` | object[] | No |  |
| `disableOfflineInstance` | boolean | No | indicate whether the component supports online instance to offlines |
| `disableOfflineInstanceRoles` | string[] | No | list of instance roles that are not allowed to be taken offline |
| `rollbackSupported` | boolean | No | indicate whether rollback is supported for this ops |
| `dependentCustomOps` | object | No |  |

## Nested Fields

### `backupMethod`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `full` | string[] | No | full backup methods |
| `incremental` | string[] | No | incremental backup methods |

### `restoreEnv`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | env name |
| `value` | string | Yes | env value |

### `dependentCustomOps`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `opsDefName` | string | No | opsDefinition name |
| `component` | string | No | component type name |
| `when` | string | No | go template conditional judgment expression, such as $.root.inPlace == true
available built-in objects that can be referenced in the expression include:
- cluster: cluster record
- ops: opsrequest object
- component: current component
- root: current object
In rebuildinstance ops, only `ops` object is available.
 |
| `params` | object[] | No | custom ops parameters |

#### `dependentCustomOps.params`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No | parameter name. |
| `value` | string | No | parameter value, you can define a go template expression to refer the variable of the current ops.
available built-in objects that can be referenced in the expression include:
- cluster: cluster record
- ops: opsrequest object
- component: current component
- root: current object
In rebuildinstance ops, only `ops` object is available.
 |

