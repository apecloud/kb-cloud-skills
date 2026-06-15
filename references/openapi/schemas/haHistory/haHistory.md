# haHistory

HA history is the records of HA operations, include `switchover` and `failover`

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `componentName` | string | Yes |  |
| `type` | string | Yes |  |
| `oldPrimary` | string | Yes |  |
| `newPrimary` | string | Yes |  |
| `status` | string | Yes |  |
| `message` | string | Yes |  |
| `operatorID` | string | No |  |
| `operatorName` | string | No |  |
| `opsrequestName` | string | No |  |
| `opsrequestNamespace` | string | No |  |
| `startAt` | string (date-time) | Yes |  |
| `endAt` | string (date-time) | Yes |  |
| `createdAt` | string (date-time) | Yes |  |

