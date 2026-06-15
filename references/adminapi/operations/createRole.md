# POST /admin/v1/organizations/{orgName}/roles

**Resource:** [role](../resources/role.md)
**Create role**
**Operation ID:** `createRole`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [roleCreate](../schemas/roleCreate/roleCreate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[role](../schemas/role/role.md)

