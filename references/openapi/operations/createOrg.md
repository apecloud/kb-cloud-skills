# POST /api/v1/organizations

**Resource:** [organization](../resources/organization.md)
**Create organization**
**Operation ID:** `createOrg`

Create a new organization

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [orgCreate](../schemas/orgCreate/orgCreate.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | OK |
| 401 | (reference) |

**Success Response Schema:**

[org](../schemas/org/org.md)

