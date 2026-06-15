# GET /api/v1/organizations/{orgName}

**Resource:** [organization](../resources/organization.md)
**Get organization**
**Operation ID:** `readOrg`

read the specified Org

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[org](../schemas/org/org.md)

