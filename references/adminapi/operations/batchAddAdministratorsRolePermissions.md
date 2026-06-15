# POST /admin/v1/administrators/roles/{roleName}/permissions/batch

**Resource:** [administrator](../resources/administrator.md)
**Batch add permissions to an administrator role**
**Operation ID:** `batchAddAdministratorsRolePermissions`

Add multiple permissions to a custom administrator role

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
| 204 | Returned when permissions are added successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

