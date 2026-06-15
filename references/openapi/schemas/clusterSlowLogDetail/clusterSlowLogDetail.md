# clusterSlowLogDetail

Slow log fields emitted by oteld

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `templateId` | string | No | Query template identifier |
| `normalizedQuery` | string | No | Normalized SQL or command template |
| `appName` | string | No | Application or client name reported by the database |
| `rowsExamined` | integer (int64) | No | Rows examined by the query |
| `rowsSent` | integer (int64) | No | Rows returned or sent by the query |
| `lockTime` | number (double) | No | Lock wait time in seconds |

