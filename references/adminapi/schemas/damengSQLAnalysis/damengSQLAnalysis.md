# damengSQLAnalysis

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `topLongExecSql` | damengLongExecSQLEntry[] | Yes | Top long-running SQL entries from V$SYSTEM_LONG_EXEC_SQLS ordered by execution time descending. |
| `topLargeMemSql` | damengLargeMemSQLEntry[] | Yes | Top high-memory SQL entries from V$SYSTEM_LARGE_MEM_SQLS ordered by memory usage descending. |

