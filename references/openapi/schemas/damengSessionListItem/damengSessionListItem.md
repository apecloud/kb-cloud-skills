# damengSessionListItem

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `sessId` | integer (int64) | Yes | Dameng session ID from V$SESSIONS. |
| `userName` | string | No | Database user name. |
| `state` | string | No | Session state (ACTIVE, IDLE, etc.). |
| `clientIp` | string | No | Client IP address. |
| `trxId` | string | No | Transaction ID. |
| `hasLock` | boolean | Yes | Whether this session has locks from V$LOCK. |
| `sqlText` | string | No | Current SQL text from V$SESSIONS. |
| `currSchema` | string | No | Current schema (database context). |
| `appName` | string | No | Application name. |
| `durationSec` | integer (int64) | No | Session duration in seconds. |
| `clientType` | string | No | Client type. |
| `autoCommit` | string | No | Auto-commit status. |

