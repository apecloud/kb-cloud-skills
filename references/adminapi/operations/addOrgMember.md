# POST /admin/v1/organizations/{orgName}/members

**Resource:** [member](../resources/member.md)
**Add member**
**Operation ID:** `addOrgMember`

Add organization with specific role

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | Name of the Org |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [orgMemberAdd](../schemas/orgMemberAdd/orgMemberAdd.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[orgMember](../schemas/orgMember/orgMember.md)

