# environmentCredentialCreate

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | Name of the environment credential |
| `usage` | [environmentCredentialUsage](environmentCredentialUsage.md) | Yes |  |
| `description` | string | No | Description of the environment credential |
| `key` | string | Yes | Key of the environment credential entry, such as accessKeyId for AWS |
| `secret` | string | Yes | Secret of the environment credential entry, such as secretAccessKey for AWS |

