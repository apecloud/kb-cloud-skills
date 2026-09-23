# postgresqlSQLFingerprint

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `queryID` | string | Yes | PostgreSQL pg_stat_statements queryid represented as a string. |
| `fingerprint` | string | Yes | Stable SQL fingerprint identifier for UI grouping. M1 uses queryID. |
| `querySummary` | string | Yes | Redacted SQL summary. Full raw SQL is intentionally not returned. |
| `calls` | integer (int64) | Yes | Number of executions accumulated by pg_stat_statements since statsReset. |
| `totalTimeMs` | number (double) | Yes | Total execution time in milliseconds accumulated by pg_stat_statements since statsReset. |
| `meanTimeMs` | number (double) | Yes | Mean execution time in milliseconds. |
| `maxTimeMs` | number (double) | Yes | Max execution time in milliseconds. |
| `rows` | integer (int64) | Yes | Rows returned or affected by the fingerprint, as reported by pg_stat_statements. |
| `database` | string | Yes | Database name resolved from pg_stat_statements.dbid when visible. |
| `user` | string | Yes | Database user name resolved from pg_stat_statements.userid when visible. |
| `topLevel` | boolean | Yes | Whether pg_stat_statements recorded the statement as top-level. Legacy PostgreSQL versions without the toplevel column report true. |

