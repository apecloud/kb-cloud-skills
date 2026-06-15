# certificate

certificates and it's config

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | [tlsName](tlsName.md) | Yes |  |
| `type` | [tlsType](tlsType.md) | Yes |  |
| `content` | string | Yes | Content of the TLS certificates |
| `expirationDays` | integer (int32) | No | Expiration days for this certificate |
| `DNS` | string[] | No | DNS name in the certificate SAN |
| `ipAddress` | string[] | No | IP address in the certificate SAN |

