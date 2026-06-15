# GET /api/v1/organizations/{orgName}/members

**Resource:** [member](../resources/member.md)
**List members**
**Operation ID:** `listOrgMember`

list members of the specified Org

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | Name of the Org |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[orgMemberList](../schemas/orgMemberList/orgMemberList.md)

