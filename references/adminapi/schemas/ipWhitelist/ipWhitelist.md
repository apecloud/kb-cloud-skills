# ipWhitelist

whitelist

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | ID of the whitelist |
| `name` | string | Yes | Name of the whitelist |
| `description` | string | No | Description |
| `addresses` | string[] | Yes | Whitelist IP Addresses |
| `createdAt` | string (date-time) | No | CreatedAt is a timestamp representing the server time when this object was created. It is not guaranteed to be set in happens-before order across separate operations. Clients may not set this value. It is represented in RFC3339 form and is in UTC.

Populated by the system. Read-only. Null for lists |
| `updatedAt` | string (date-time) | No | UpdatedAt is a timestamp representing the server time when this object was created. It is not guaranteed to be set in happens-before order across separate operations. Clients may not set this value. It is represented in RFC3339 form and is in UTC.

Populated by the system. Read-only. Null for lists |

