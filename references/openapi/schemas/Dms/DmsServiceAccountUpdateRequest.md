# DmsServiceAccountUpdateRequest

MinIO service account access-key update request

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `status` | [DmsServiceAccountStatus](DmsServiceAccountStatus.md) | No |  |
| `expiration` | string (date-time) | No | Optional service account expiration time. Use the Unix epoch to clear expiration. |

