# tlsOption

TLS options

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `issuer` | [certificateIssuer](certificateIssuer.md) | Yes |  |
| `serviceName` | string[] | No | the service name that will be set in certificate SAN |
| `caContent` | string | No | CA certificate content |
| `certificateContent` | string | No | Certificate content |
| `privateKeyContent` | string | No | Private key content |

