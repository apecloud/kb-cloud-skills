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
| `customAnnotations` | boolean | No | Whether to show the component annotations editor during cluster creation. Omitted or false hides the editor. This is a UI visibility hint and does not restrict the cluster creation API. Applies to this component in every engine mode, including sharding templates, on KubeBlocks 0.9 and 1.0. |
| `customLabels` | boolean | No | Whether to show the component labels editor during cluster creation. Omitted or false hides the editor. This is a UI visibility hint and does not restrict the cluster creation API. Applies to this component in every engine mode, including sharding templates, on KubeBlocks 0.9 and 1.0. |
| `customSecret` | boolean | No | whether the component supports custom secret |

## Nested Fields

### `version`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `componentVersionName` | string | Yes | component version name |
| `minorVersion` | object | No |  |
| `majorVersion` | object | Yes |  |
| `architecture` | [componentVersionArchitecture](componentVersionArchitecture.md) | No |  |
| `blockedUpgradeFrom` | object[] | No | Upgrades that must not be offered or accepted for this component, keyed by the service version the cluster currently runs. Use it when a target version is not a drop-in replacement for a source version, for example when the source image ships modules the target image no longer carries. Upgrades matching no rule stay untouched. |

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

#### `version.blockedUpgradeFrom`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | string | Yes | Pattern of the service version the cluster currently runs. Supports exact version "7.4.7", version prefix "7.4", and comparisons ">=7.4.5", ">7.4.4", "<=7.4.7", "<7.4.8". |
| `to` | string | No | Pattern of the service version the upgrade is blocked to, with the same syntax as from. Omit to block every upgrade target, which makes from the end of the line for the component. |

