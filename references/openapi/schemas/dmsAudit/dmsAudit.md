# dmsAudit

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes |  |
| `orgName` | string | Yes |  |
| `clusterId` | string | Yes |  |
| `clusterName` | string | Yes |  |
| `datasourceId` | string | No |  |
| `userId` | string | No | Absent for migrated history with unknown actor. |
| `userName` | string | Yes |  |
| `databaseUser` | string | No | Database connection account captured at operation time. Empty for historical records or connections without a named account. |
| `engine` | string | Yes |  |
| `database` | string | Yes |  |
| `operation` | string | Yes |  |
| `statement` | string | Yes |  |
| `clientIp` | string | No |  |
| `sessionId` | string | No | Native database session ID; see individual statements when a batch uses multiple connections. |
| `risk` | [dmsAuditRisk](dmsAuditRisk.md) | No |  |
| `tableNames` | string[] | No |  |
| `errorMessage` | string | No |  |
| `rowsAffected` | integer (int64) | No |  |
| `statements` | dmsAuditStatement[] | No |  |
| `status` | [dmsAuditStatus](dmsAuditStatus.md) | Yes |  |
| `createdAt` | string (date-time) | Yes |  |
| `finishedAt` | string (date-time) | No |  |
| `durationMs` | integer (int64) | No |  |

