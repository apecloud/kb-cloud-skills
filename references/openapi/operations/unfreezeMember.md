# POST /api/v1/organizations/{orgName}/members/{memberId}/unfreeze

**Resource:** [organization](../resources/organization.md)
**unfreeze the member in org**
**Operation ID:** `unfreezeMember`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `memberId` | path | string | Yes | ID of the member |

## Responses

| Status | Description |
|--------|-------------|
| 204 | OK |
| 401 | (reference) |
| 403 | (reference) |

