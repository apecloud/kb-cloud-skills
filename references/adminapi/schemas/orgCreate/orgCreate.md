# orgCreate

OrgCreate is the payload for organization creation

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | No | The description of the organization |
| `displayName` | string | No | The display name of the organization |
| `name` | string | Yes | The full, unique name of this Object in the format organizations/{name}, set during creation. name must be a valid RFC 1123 compliant DNS label |

