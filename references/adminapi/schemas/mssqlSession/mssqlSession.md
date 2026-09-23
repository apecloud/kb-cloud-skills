# mssqlSession

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `sessionId` | integer (int64) | Yes |  |
| `startedAt` | string | Yes | Opaque SQL Server local start time, used to detect session or request reuse. Pass back unchanged; it is not a UTC timestamp. |
| `status` | string | Yes |  |
| `user` | string | Yes |  |
| `host` | string | Yes |  |
| `application` | string | Yes |  |
| `client` | string | Yes |  |
| `database` | string | Yes |  |
| `openTransactions` | integer (int64) | Yes |  |
| `transactionSeconds` | integer (int64) | Yes |  |
| `lastSql` | string | Yes | Most recent batch on the connection, not necessarily the SQL that acquired its locks. Truncated to 8192 characters. |
| `lastSqlTruncated` | boolean | Yes |  |
| `requests` | mssqlRequest[] | Yes |  |
| `requestsTruncated` | boolean | Yes |  |

