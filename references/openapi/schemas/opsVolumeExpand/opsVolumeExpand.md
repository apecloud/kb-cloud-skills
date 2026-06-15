# opsVolumeExpand

OpsVolumeExpand is the payload to expand volume for a KubeBlocks cluster

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `component` | string | Yes |  |
| `volumes` | object[] | Yes |  |

## Nested Fields

### `volumes`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | volume name |
| `storage` | string | Yes | Storage size, the unit is Gi. |

