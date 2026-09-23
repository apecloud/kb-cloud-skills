# postgresqlSession

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `pid` | integer (int64) | Yes |  |
| `user` | string | Yes |  |
| `database` | string | Yes |  |
| `applicationName` | string | Yes |  |
| `clientAddr` | string | Yes | Client address. |
| `clientPort` | string | Yes | Client port. |
| `state` | string | Yes |  |
| `waitEventType` | string | Yes |  |
| `waitEvent` | string | Yes |  |
| `backendStart` | string | No | Backend start timestamp if available. |
| `queryStart` | string | No | Query start timestamp if available. |
| `xactStart` | string | No | Transaction start timestamp if available. |
| `durationSeconds` | integer (int64) | Yes |  |
| `xactDurationSeconds` | integer (int64) | Yes |  |
| `queryDigest` | string | Yes |  |
| `querySummary` | string | Yes |  |
| `backendType` | string | Yes |  |

