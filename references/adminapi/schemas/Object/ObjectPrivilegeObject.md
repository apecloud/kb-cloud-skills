# ObjectPrivilegeObject

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `target` | [ObjectPrivilegeTarget](ObjectPrivilegeTarget.md) | Yes |  |
| `identity` | string | Yes | Display identity, including PostgreSQL routine input argument types. Use target for operations; identity is never accepted as SQL. |

