# ObjectPrivilegePrerequisiteCheck

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `target` | [ObjectPrivilegeTarget](ObjectPrivilegeTarget.md) | Yes |  |
| `privilege` | string | Yes |  |
| `status` | [ObjectPrivilegePrerequisiteStatus](ObjectPrivilegePrerequisiteStatus.md) | Yes |  |
| `reason` | string | No | Optional explanation. Checks are not a complete proof of executable access. Missing checks do not imply granted. |

