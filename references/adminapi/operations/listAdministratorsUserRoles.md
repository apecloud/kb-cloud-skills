# GET /admin/v1/administrators/{administratorID}/roles

**Resource:** [administrator](../resources/administrator.md)
**List roles of an administrator user**
**Operation ID:** `listAdministratorsUserRoles`

List all roles assigned to a specific administrator user

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `administratorID` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[adminRoleList](../schemas/adminRoleList/adminRoleList.md)

