# DELETE /api/v1/organizations/{orgName}/roles/{roleName}/permissions/batch

**Resource:** [role](../resources/role.md)
**Batch remove permissions from a role**
**Operation ID:** `batchRemoveRolePermissions`

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
| 204 | Returned when permissions are removed successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

