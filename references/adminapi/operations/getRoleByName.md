# GET /admin/v1/organizations/{orgName}/roles/{roleName}

**Resource:** [role](../resources/role.md)
**Get role by name**
**Operation ID:** `getRoleByName`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `roleName` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[role](../schemas/role/role.md)

