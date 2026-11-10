# ObjectPrivilegeGrant

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes |  |
| `column` | string | No | Empty means an object-level privilege. |
| `grantable` | boolean | Yes |  |
| `grantor` | string | No | PostgreSQL ACL grantor. Omitted for MySQL and effective privilege results. |

