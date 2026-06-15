# PATCH /api/v1/organizations/{orgName}

**Resource:** [organization](../resources/organization.md)
**Update organization**
**Operation ID:** `patchOrg`

partially update the specified Org

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [orgUpdate](../schemas/orgUpdate/orgUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 201 | Created |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[org](../schemas/org/org.md)

