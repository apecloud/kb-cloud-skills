# DELETE /api/v1/organizations/{orgName}/tags/{tagId}

**Resource:** [clusterTag](../resources/clusterTag.md)
**Delete tag**
**Operation ID:** `deleteTag`

delete cluster tag

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `tagId` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when project is deleted successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

