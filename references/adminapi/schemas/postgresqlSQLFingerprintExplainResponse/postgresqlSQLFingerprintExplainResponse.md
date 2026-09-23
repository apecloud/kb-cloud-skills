# postgresqlSQLFingerprintExplainResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `queryID` | string | Yes | PostgreSQL pg_stat_statements queryid represented as a string. |
| `fingerprint` | string | Yes | Stable SQL fingerprint identifier for UI grouping. Currently aligned with PostgreSQL pg_stat_statements queryid. |
| `database` | string | Yes | Database name from the requested SQL fingerprint identity. |
| `user` | string | Yes | Database user from the requested SQL fingerprint identity. |
| `topLevel` | boolean | Yes | Top-level flag from the requested SQL fingerprint identity. |
| `statementSource` | string | No | Server-side source used to resolve the parameterized SQL statement. Raw SQL is not returned. |
| `statementResolvedAt` | string | No | Timestamp when the parameterized SQL statement was resolved. |
| `planMode` | [DmsExecutionPlanPlanningMode](DmsExecutionPlanPlanningMode.md) | Yes |  |
| `parameterized` | boolean | Yes | Whether generic parameterized planning was used (planMode is generic). False means standard planning, not that historical parameter values were used. This endpoint never retrieves historical parameter values. |
| `parameterCount` | integer (int64) | No | Number of parameters when DMS can determine it. It may be omitted for PostgreSQL generic-plan paths that do not expose the count. |
| `explainResult` | [DmsExecutionPlanResult](DmsExecutionPlanResult.md) | Yes |  |

