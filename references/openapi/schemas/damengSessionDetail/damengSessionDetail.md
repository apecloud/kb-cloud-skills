# damengSessionDetail

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `sessId` | integer (int64) | Yes | Dameng session ID from V$SESSIONS. |
| `userName` | string | No | Database user name. |
| `state` | string | No | Session state (ACTIVE, IDLE, etc.). |
| `clientIp` | string | No | Client IP address. |
| `clientType` | string | No | Client type. |
| `createTime` | string | No | Session creation time. |
| `lastSendTime` | string | No | Last SQL send time. |
| `sqlText` | string | No | Current or last SQL text from V$SESSIONS. |
| `fullSql` | string | No | Full SQL text via SF_GET_SESSION_SQL. |
| `trxId` | string | No | Transaction ID. |
| `trxDurationSec` | integer (int64) | No | Seconds since last SQL send time. |
| `appName` | string | No | Application name. |
| `currSchema` | string | No | Current schema. |
| `autoCommit` | string | No | Auto-commit status (Y/N). |

