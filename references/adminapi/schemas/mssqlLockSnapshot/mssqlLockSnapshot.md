# mssqlLockSnapshot

Bounded live DMV observations. Edges are SQL Server reported blocking identifiers. Collection is not atomic; graph cycles are not historical deadlock evidence.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `capturedAt` | string | Yes |  |
| `sessions` | mssqlSession[] | Yes |  |
| `waits` | mssqlWait[] | Yes |  |
| `locks` | mssqlLock[] | Yes |  |
| `truncated` | boolean | Yes |  |

