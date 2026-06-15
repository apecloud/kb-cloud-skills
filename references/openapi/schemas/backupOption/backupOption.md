# backupOption

If present, it must be set defaultMethod and fullMethod

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `defaultMethod` | string | Yes |  |
| `defaultComponent` | string | No | If set, the default backup method will be applied to the specified component.
If not set, the default backup method will be applied to all components.
 |
| `defaultBPTSelector` | object | No | selector for the default backup policy template. this is necessary when referencing other addon components |
| `restoreOption` | object | No |  |
| `offlineBackupOption` | object | No |  |
| `backupParameters` | [parameters](parameters.md) | No |  |
| `restoreParameters` | [parameters](parameters.md) | No |  |
| `fullMethod` | backupMethodOption[] | Yes |  |
| `incrementalMethod` | backupMethodOption[] | No |  |
| `continuousMethod` | backupMethodOption[] | No |  |
| `selectiveMethod` | selectiveMethodOption[] | No | Selective backup methods that support backing up specific objects |

## Nested Fields

### `restoreOption`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `crossModeRecovery` | string[] | No | cross mode recovery options |

### `offlineBackupOption`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `useParentDirAsBackupPath` | boolean | No | whether to use the parent directory of the backup path as the actual backup path |
| `supported` | boolean | No | whether offline backup is supported |
| `rootUser` | string | No | the root user for offline backup |
| `supportEmptyPassword` | boolean | No | whether to support empty password for the root user in offline backup |
| `backupMethod` | string | No | the backup method for offline backup |
| `componentName` | string | No | the component name for offline backup |
| `status` | object | No |  |
| `modes` | string[] | No | the modes that offline backup supports. if not set, it means all modes are supported. |

