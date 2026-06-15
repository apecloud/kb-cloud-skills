# DELETE /admin/v1/administrators/roles/{roleName}/permissions/batch

**Resource:** [administrator](../resources/administrator.md)
**Batch remove permissions from an administrator role**
**Operation ID:** `batchRemoveAdministratorsRolePermissions`

Remove multiple permissions from a custom administrator role

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
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

