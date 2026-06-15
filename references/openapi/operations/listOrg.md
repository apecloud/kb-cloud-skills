# GET /api/v1/organizations

**Resource:** [organization](../resources/organization.md)
**List organizations of current user**
**Operation ID:** `listOrg`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `pageToken` | query | string | No | The pagination token in the List request |
| `pageSize` | query | string | No | The pagination size in the List request. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |

**Success Response Schema:**

[userOrgList](../schemas/userOrgList/userOrgList.md)

