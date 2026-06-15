# modeObjectStorage

object storage related configs


**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | No | if object storage is enabled for this mode |
| `serviceRef` | [modeServiceRef](modeServiceRef.md) | No |  |
| `additionalHelmValuePath` | object | No | The path in helm values that some object storage config will use. If empty, the values will not be set. |

## Nested Fields

### `additionalHelmValuePath`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `bucket` | string | Yes | the bucket name for the object storage |
| `path` | string | No | root path where cluster stores data in the bucket. This field is not user-provided.
It is always set to cluster id. If not set, it means the engine does not support specify a path.
 |
| `usePathStyle` | string | No | whether the object storage is using path style or virtual host style.
If not set, it means the engine does not need this option.
 |
| `region` | string | No | Region to use. If not set, it means the engine does not need this option.
 |

