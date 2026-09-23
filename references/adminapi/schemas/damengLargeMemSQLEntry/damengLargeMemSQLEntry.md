# damengLargeMemSQLEntry

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `sqlText` | string | Yes | SQL text from V$SYSTEM_LARGE_MEM_SQLS. |
| `memUsedKb` | integer (int64) | Yes | Memory used in kilobytes. |
| `sessionId` | string | No | Session ID, when available. |
| `sqlId` | string | No | SQL ID, when available. |
| `finishTime` | string | No | SQL finish time in UTC, when available. |
| `nRuns` | integer (int64) | Yes | Number of executions. |

