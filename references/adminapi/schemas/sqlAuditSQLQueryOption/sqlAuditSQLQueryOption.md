# sqlAuditSQLQueryOption

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `sql` | string | Yes | SQL query to check audit log status |
| `enabledValues` | string[] | No | List of query result values that indicate SQL audit is enabled (case-insensitive comparison). If not provided, defaults to ["1", "true", "on", "enabled", "yes"]. |
| `disabledValues` | string[] | No | List of query result values that indicate SQL audit is disabled (case-insensitive comparison). If not provided, defaults to ["0", "false", "off", "disabled", "no"]. |

