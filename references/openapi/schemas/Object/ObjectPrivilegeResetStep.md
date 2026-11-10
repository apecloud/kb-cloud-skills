# ObjectPrivilegeResetStep

One ordered, engine-generated step of an account privilege reset.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `databaseName` | string | No | Connection database in which this statement must run. Omitted when no particular database is required, as with MySQL account-wide REVOKE. This is execution context, not the scope of objects affected by the SQL. |
| `sql` | string | Yes | Engine-generated statement for display (SQL, or a native MongoDB command encoded as JSON). Callers cannot submit or modify these steps for execution; reset rebuilds the plan from current grants. |

