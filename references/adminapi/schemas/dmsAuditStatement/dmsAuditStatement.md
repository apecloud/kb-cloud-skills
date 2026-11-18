# dmsAuditStatement

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `sequence` | integer | Yes |  |
| `statement` | string | Yes |  |
| `database` | string | Yes |  |
| `tableNames` | string[] | Yes |  |
| `sessionId` | string | No |  |
| `risk` | [dmsAuditRisk](dmsAuditRisk.md) | Yes |  |
| `status` | [dmsAuditStatus](dmsAuditStatus.md) | Yes |  |
| `errorMessage` | string | Yes |  |
| `durationMs` | integer (int64) | No |  |
| `rowsAffected` | integer (int64) | No |  |
| `startedAt` | string (date-time) | No |  |
| `finishedAt` | string (date-time) | No |  |

