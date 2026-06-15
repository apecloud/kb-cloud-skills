# PATCH /admin/v1/organizations/{orgName}/members/{memberId}

**Resource:** [member](../resources/member.md)
**Update member role**
**Operation ID:** `patchOrgMember`

Only authenticated organization admins can update the member's role

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `memberId` | path | string | Yes | ID of the member |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [orgMemberUpdate](../schemas/orgMemberUpdate/orgMemberUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[orgMember](../schemas/orgMember/orgMember.md)

