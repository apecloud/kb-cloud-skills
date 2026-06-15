# apikeyWithSK

APIKeyWithSK is the response for creating an APIKey

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `accessKey` | string | Yes | The accessKey of the APIKey |
| `secretKey` | string | Yes | The secretKey of the APIKey |
| `description` | string | Yes | The description of the APIKey |
| `expiredAt` | string (date-time) | No | The expired time of APIKey |
| `createAt` | string (date-time) | Yes | The create time of APIKey |

