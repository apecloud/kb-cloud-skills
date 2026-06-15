# dashboardOption

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `component` | string | Yes |  |
| `dashboardUid` | string | Yes |  |
| `variables` | object | Yes |  |
| `instancePanels` | object[] | No |  |

## Nested Fields

### `instancePanels`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `role` | string | No |  |
| `panels` | object[] | No |  |

#### `instancePanels.panels`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | No |  |
| `id` | string | No |  |

