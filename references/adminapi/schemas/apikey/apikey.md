# apikey

APIKey is the key for API access

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `accessKey` | string | Yes | The name of the APIKey |
| `description` | string | Yes | The description for APIKey |
| `expiredAt` | string (date-time) | No | The expired time of APIKey, return empty without setting duration |
| `createAt` | string (date-time) | Yes | The create time of APIKey |

