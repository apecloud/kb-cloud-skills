# sqlAuditSQLOption

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `query` | [sqlAuditSQLQueryOption](sqlAuditSQLQueryOption.md) | Yes |  |
| `enable` | string[] | Yes | SQL statements to enable audit log. Multiple statements will be joined and executed. |
| `disable` | string[] | Yes | SQL statements to disable audit log. Multiple statements will be joined and executed. |
| `user` | string | No | Specific user account name to execute SQL statements. If not provided, uses the default datasource account. |

