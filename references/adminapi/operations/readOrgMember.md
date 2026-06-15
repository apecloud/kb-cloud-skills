# GET /admin/v1/organizations/{orgName}/members/{memberId}

**Resource:** [member](../resources/member.md)
**Get member**
**Operation ID:** `readOrgMember`

read the specified OrgMember

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `memberId` | path | string | Yes | ID of the member |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[orgMember](../schemas/orgMember/orgMember.md)

