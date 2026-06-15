# DmsExcludeConstraint

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No | The name of the exclude constraint |
| `indexMethod` | string | No | The index method (e.g., GIST, BTREE) |
| `exclude` | object[] | No |  |

## Nested Fields

### `exclude`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `columns` | string | No | The column(s) involved in the exclusion |
| `operator` | string | No | The operator used in the exclusion |

