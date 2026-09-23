# mssqlWait

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `sessionId` | integer (int64) | Yes |  |
| `requestId` | integer (int64) | Yes | Request ID, or -1 when a waiting task cannot be associated with a live request. |
| `blockingSessionId` | integer (int64) | Yes | SQL Server blocking owner. Negative values are special owners, not session IDs. |
| `waitType` | string | Yes |  |
| `waitMs` | integer (int64) | Yes |  |
| `resource` | string | Yes |  |
| `source` | string | Yes |  |

