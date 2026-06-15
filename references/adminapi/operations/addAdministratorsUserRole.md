# POST /admin/v1/administrators/{administratorID}/roles

**Resource:** [administrator](../resources/administrator.md)
**Add a role to an administrator user**
**Operation ID:** `addAdministratorsUserRole`

Assign a role to a specific administrator user

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `administratorID` | path | string | Yes |  |

## Request Body

**Content Types:** `application/json`

**Schema** (inline):

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `roleName` | string | Yes | The name of the role to assign |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when role is assigned successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 404 | (reference) |

