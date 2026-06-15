# DELETE /admin/v1/organizations/{orgName}/members/{memberId}

**Resource:** [member](../resources/member.md)
**Delete member**
**Operation ID:** `deleteOrgMember`

delete a Org Member

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | Name of the Org |
| `memberId` | path | string | Yes | ID of the member |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when project is deleted successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

