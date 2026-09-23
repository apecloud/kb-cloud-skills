# DmsServiceAccount

MinIO service account access-key

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `userName` | string | No | MinIO user that owns the service account. |
| `accessKey` | string | No | Service account access key. |
| `secretKey` | string | No | Secret key returned only by create. |
| `status` | string | No | Service account status. |
| `name` | string | No | Display name of the service account. |
| `description` | string | No | Description of the service account. |
| `expiration` | string (date-time) | No | Service account expiration time. |
| `policy` | string | No | Service account policy text. |
| `impliedPolicy` | boolean | No | Whether the policy is implied from the parent user. |

