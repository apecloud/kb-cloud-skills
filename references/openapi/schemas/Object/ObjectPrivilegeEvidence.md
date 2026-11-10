# ObjectPrivilegeEvidence

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `databaseName` | string | No | Connection database for native privilege evidence. |
| `kind` | string | Yes |  |
| `format` | string | Yes |  |
| `items` | string[] | Yes | Read-only native evidence; never replay as a privilege mutation. |

