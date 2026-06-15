# environmentCredential

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | Name of the environment credential |
| `usage` | [environmentCredentialUsage](environmentCredentialUsage.md) | Yes |  |
| `key` | string | Yes | Key of the environment credential entry, such as accessKeyId for AWS |
| `secret` | string | Yes | Secret of the environment credential entry, such as secretAccessKey for AWS |
| `description` | string | No | Description of the environment credential |
| `permissionTips` | string[] | No | Text hints describing the permissions this credential should have for its usage. |
| `createdAt` | string (date-time) | Yes | CreatedAt is a timestamp representing the server time when this object was created. It is represented in RFC3339 form and is in UTC. |
| `updatedAt` | string (date-time) | Yes | UpdatedAt is a timestamp representing the server time when this object was updated. It is represented in RFC3339 form and is in UTC. |

