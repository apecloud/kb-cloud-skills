# ESSecurityRoleMapping

Native Elasticsearch security role mapping. At least one of roles or role_templates must be non-empty.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | Yes |  |
| `roles` | string[] | No |  |
| `role_templates` | ESSecurityRoleTemplate[] | No |  |
| `rules` | object | Yes |  |
| `metadata` | object | No |  |

