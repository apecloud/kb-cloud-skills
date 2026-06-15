# PATCH /admin/v1/platformParameters

**Resource:** [platformParameter](../resources/platformParameter.md)
**update platformParameters**
**Operation ID:** `updatePlatformParameters`

## Request Body

**Content Types:** `application/json`

**Schema:** Array of [platformParameterUpdate](../schemas/platformParameterUpdate/platformParameterUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

Array of [platformParameter](../schemas/platformParameter/platformParameter.md)

