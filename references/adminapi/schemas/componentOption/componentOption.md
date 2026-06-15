# componentOption

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cloudShellType` | string | No | cloud shell type |
| `name` | string | Yes | component type |
| `matchRegex` | string | No | Determine whether the componentDef of kb-cluster belongs to this component type through this matching regularization.
if not set, componentDef must be equal to component type.
 |
| `title` | [localizedDescription](localizedDescription.md) | Yes |  |
| `order` | integer | Yes |  |
| `roleOrder` | string[] | No |  |
| `disasterRecoveryRoleOrder` | string[] | No |  |
| `version` | object | Yes |  |
| `main` | boolean | No | Main component flag |
| `customSecret` | boolean | No | whether the component supports custom secret |

## Nested Fields

### `version`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `componentVersionName` | string | Yes | component version name |
| `minorVersion` | object | No |  |
| `majorVersion` | object | Yes |  |
| `architecture` | [componentVersionArchitecture](componentVersionArchitecture.md) | No |  |

#### `version.minorVersion`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `default` | string | No | default version. |
| `rollback` | boolean | No | determine whether minor version can be rolled back. |
| `disableRollbackPreRelease` | boolean | No | disable roll back the preRelease minor version. |

#### `version.majorVersion`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `default` | string | No | default major version. |
| `rule` | string | Yes | ServiceVersion uses semver syntax(X Y.Z), such MySQL 5.7.4 and PG 14.8.0.
Currently supports [X, X.Y, X.Y.Z] formats to determine major versions of the engine from the serviceVersion
 |
| `versionMapping` | object[] | No |  |

