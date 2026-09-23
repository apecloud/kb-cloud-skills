# mssqlRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `requestId` | integer (int64) | Yes |  |
| `startedAt` | string | Yes | Opaque SQL Server local start time, used to detect session or request reuse. Pass back unchanged; it is not a UTC timestamp. |
| `status` | string | Yes |  |
| `command` | string | Yes |  |
| `database` | string | Yes |  |
| `sql` | string | Yes | Current statement extracted with byte offsets. Truncated to 8192 characters. |
| `sqlTruncated` | boolean | Yes |  |
| `elapsedMs` | integer (int64) | Yes |  |
| `cpuMs` | integer (int64) | Yes |  |
| `reads` | integer (int64) | Yes |  |
| `logicalReads` | integer (int64) | Yes |  |
| `writes` | integer (int64) | Yes |  |
| `waitType` | string | Yes |  |
| `waitMs` | integer (int64) | Yes |  |
| `waitResource` | string | Yes |  |
| `blockingSessionId` | integer (int64) | Yes |  |

