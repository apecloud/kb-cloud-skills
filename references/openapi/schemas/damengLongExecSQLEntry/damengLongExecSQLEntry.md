# damengLongExecSQLEntry

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `sqlText` | string | Yes | SQL text from V$SYSTEM_LONG_EXEC_SQLS. |
| `execTimeMs` | integer (int64) | Yes | Execution time in milliseconds. |
| `sessionId` | string | No | Session ID, when available. |
| `sqlId` | string | No | SQL ID, when available. |
| `nRuns` | integer (int64) | Yes | Number of executions. |
| `finishTime` | string | No | SQL finish time in UTC, when available. |

