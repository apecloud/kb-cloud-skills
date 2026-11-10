# InfluxDBToken

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes |  |
| `userID` | string | Yes |  |
| `orgID` | string | Yes |  |
| `description` | string | Yes |  |
| `status` | [InfluxDBTokenStatus](InfluxDBTokenStatus.md) | Yes |  |
| `permissions` | InfluxDBPermission[] | Yes |  |
| `editable` | boolean | Yes | Only explicit bucket-scoped tokens can be changed. |

