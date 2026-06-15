# GET /api/v1/organizations/{orgName}/permissions

**Resource:** [member](../resources/member.md)
**List permissions of a member**
**Operation ID:** `listOrgMemberPermission`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The name of the organization |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[permissionList](../schemas/permissionList/permissionList.md)

