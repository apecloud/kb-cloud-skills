# modeOption

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes |  |
| `title` | [localizedDescription](localizedDescription.md) | Yes |  |
| `description` | [localizedDescription](localizedDescription.md) | Yes |  |
| `schedulingPolicy` | object | No |  |
| `compatibleKubeblocksVersion` | [modeCompatibleKubeblocksVersion](modeCompatibleKubeblocksVersion.md) | No |  |
| `components` | modeComponent[] | Yes |  |
| `proxy` | object | No |  |
| `versions` | string[] | No |  |
| `extra` | object | No |  |
| `serviceRefs` | modeServiceRef[] | No |  |
| `objectStorage` | [modeObjectStorage](modeObjectStorage.md) | No |  |
| `valuesMappings` | object | No |  |
| `hideOnCreate` | boolean | No | whether the mode is hidden for creation |
| `transition` | engineModeTransition[] | No | Valid mode transitions from this mode. |

## Nested Fields

### `schedulingPolicy`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `componentAntiAffinity` | string[] | No | when component names are specified in componentAntiAffinity, those components will be scheduled with anti-affinity rules
applied to ensure they are spread across different nodes, especially when resource dispersion is enabled.
 |

### `proxy`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | Yes |  |

### `valuesMappings`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `compatibleKBVersions` | string[] | No |  |
| `mappings` | object[] | No |  |

#### `valuesMappings.mappings`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `component` | string | No |  |
| `sourceKey` | string | Yes |  |
| `sourceValue` | any | No | Can be any type (string, number, boolean, object, etc.) |
| `targetKey` | string | Yes |  |
| `targetValue` | any | No | Can be any type (string, number, boolean, object, etc.) |

