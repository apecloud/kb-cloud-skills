# DmsServiceAccountCreateRequest

MinIO service account access-key create request

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `userName` | string | Yes | MinIO user that owns the service account. |
| `accessKey` | string | No | Optional fixed access key. If omitted, MinIO generates it. |
| `secretKey` | string | No | Optional fixed secret key. If omitted, MinIO generates it. |
| `name` | string | No | Display name of the service account. |
| `description` | string | No | Description of the service account. |
| `expiration` | string (date-time) | No | Optional service account expiration time. |

