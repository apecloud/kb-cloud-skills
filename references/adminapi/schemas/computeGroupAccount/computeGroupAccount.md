# computeGroupAccount

Grants reported by the engine can include role inheritance. Revoking a direct grant does not remove inherited permissions.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `identity` | string | No |  |
| `accountName` | string | No |  |
| `manageable` | boolean | No |  |
| `globalGrants` | string | No |  |
| `computeGrants` | string | No |  |
| `roles` | string | No |  |
| `isDefault` | boolean | No |  |

