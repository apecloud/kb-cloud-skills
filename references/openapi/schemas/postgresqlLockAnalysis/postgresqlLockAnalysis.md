# postgresqlLockAnalysis

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `selectedSession` | [postgresqlSession](postgresqlSession.md) | Yes |  |
| `directBlockingSessions` | postgresqlSession[] | Yes | Sessions that directly block the selected session in the current snapshot. |
| `directBlockedSessions` | postgresqlSession[] | Yes | Sessions that are directly blocked by the selected session in the current snapshot. |
| `lockRows` | postgresqlLockRow[] | Yes |  |
| `waitGraph` | [postgresqlWaitGraph](postgresqlWaitGraph.md) | Yes |  |
| `deadlock` | [postgresqlDeadlockEvidence](postgresqlDeadlockEvidence.md) | Yes |  |
| `cannotProve` | boolean | Yes | Whether the current snapshot cannot prove the lock relationship conclusively. |
| `warnings` | string[] | Yes |  |
| `capturedAt` | string | Yes | Snapshot capture timestamp in UTC. |

