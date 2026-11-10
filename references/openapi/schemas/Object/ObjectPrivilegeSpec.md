# ObjectPrivilegeSpec

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | Native keyword from the capability for the requested object type. |
| `columns` | string[] | No | Exact columns, supported only on table/view objects. Empty means object-level privileges. |

