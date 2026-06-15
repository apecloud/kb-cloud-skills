# DELETE /api/v1/organizations/{orgName}

**Resource:** [organization](../resources/organization.md)
**Delete organization**
**Operation ID:** `deleteOrg`

partially delete the specified org

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when org is deleted successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |

