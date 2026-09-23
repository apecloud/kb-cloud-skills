# postgresqlWaitGraphEdge

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `blockingPid` | integer (int64) | Yes | PID that blocks another session. |
| `blockedPid` | integer (int64) | Yes | PID that is blocked by another session. |
| `evidence` | [postgresqlWaitGraphEdgeEvidence](postgresqlWaitGraphEdgeEvidence.md) | Yes |  |

