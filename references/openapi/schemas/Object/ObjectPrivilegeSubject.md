# ObjectPrivilegeSubject

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | Exact native database account or role name. |
| `type` | [ObjectPrivilegeSubjectType](ObjectPrivilegeSubjectType.md) | Yes |  |
| `qualifiers` | object | No | Engine-declared native identity qualifiers. MySQL host defaults to %. Unknown keys are rejected, including empty values. |

