# damengLockAnalysis

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `selectedSession` | [damengSessionDetail](damengSessionDetail.md) | Yes |  |
| `locks` | damengLockRow[] | Yes | Lock records for the selected session's transaction. |
| `capturedAt` | string | Yes | Backend collection timestamp in UTC. |

