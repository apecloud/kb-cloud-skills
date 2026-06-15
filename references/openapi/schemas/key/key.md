# key

mutiple kv pair

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No | The unique identifier of the key. |
| `name` | string | No | The name of the key. |
| `algorithm` | [encryptionAlgorithm](encryptionAlgorithm.md) | No |  |
| `keyUsage` | [encryptionKeyUsage](encryptionKeyUsage.md) | No |  |
| `clusters` | string[] | No | the clusters which use the key |
| `backups` | string[] | No | the backups which use the key |
| `createdAt` | string (date-time) | No | The creation timestamp of the key. |
| `updatedAt` | string (date-time) | No | The last update timestamp of the key. |
| `key` | string | No | the key content. This field will not be included in list/get response. |

