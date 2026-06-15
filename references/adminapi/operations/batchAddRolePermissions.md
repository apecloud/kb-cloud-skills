# POST /admin/v1/organizations/{orgName}/roles/{roleName}/permissions/batch

**Resource:** [role](../resources/role.md)
**Batch add permissions to a role**
**Operation ID:** `batchAddRolePermissions`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `roleName` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema** (inline):

Array

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when permissions are added successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |

