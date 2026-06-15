# adminRole

Administrator Role information

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | The name of the role |
| `type` | string | Yes | The type of the role (built-in or customized) |
| `displayName` | [localizedDescription](localizedDescription.md) | No |  |
| `description` | [localizedDescription](localizedDescription.md) | No |  |
| `createdAt` | string (date-time) | No | The time when the role was created. Read-Only |
| `updatedAt` | string (date-time) | No | The time when the role was updated. Read-Only |

