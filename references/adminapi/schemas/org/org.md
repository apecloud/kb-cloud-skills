# org

Org info

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `createdAt` | string (date-time) | Yes | CreatedAt is a timestamp representing the server time when this object was created. It is not guaranteed to be set in happens-before order across separate operations. Clients may not set this value. It is represented in RFC3339 form and is in UTC.

Populated by the system. Read-only. Null for lists |
| `description` | string | No | The description of the organization |
| `displayName` | string | No | The display name of the organization |
| `id` | string | No | The ID of the organization |
| `name` | string | Yes | The full, unique name of this Object in the format organizations/{name}, set during creation. name must be a valid RFC 1123 compliant DNS label |
| `updatedAt` | string (date-time) | Yes | UpdatedAt is a timestamp representing the server time when this object was created. It is not guaranteed to be set in happens-before order across separate operations. Clients may not set this value. It is represented in RFC3339 form and is in UTC.

Populated by the system. Read-only. Null for lists |
| `enabled` | boolean | Yes | return true if the organization is enabled |

