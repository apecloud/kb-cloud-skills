# sqlAuditResponse

Response after updating SQL audit log status

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | Yes | Whether SQL audit log is enabled after the operation |
| `taskId` | string | No | Task ID if the operation is asynchronous (e.g. reconfigure) |

