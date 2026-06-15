# GET /api/v1/organizations/{orgName}/roles

**Resource:** [role](../resources/role.md)
**List roles of a organization**
**Operation ID:** `listRoles`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[roleList](../schemas/roleList/roleList.md)

