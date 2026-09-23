# damengLockRow

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `trxId` | integer (int64) | Yes | Transaction ID holding the lock. |
| `lockType` | string | No | Lock type. |
| `lockMode` | string | No | Lock mode. |
| `sessId` | integer (int64) | No | Session ID associated with this lock. |
| `clientIp` | string | No | Client IP address for the session. |
| `sqlText` | string | No | SQL text for the session. |
| `userName` | string | No | User name for the session. |

