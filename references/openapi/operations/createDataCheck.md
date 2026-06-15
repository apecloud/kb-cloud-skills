# POST /api/v1/organizations/{orgName}/checks

**Resource:** [dataReplication](../resources/dataReplication.md)
**Create a data check**
**Operation ID:** `createDataCheck`

Create an independent data check. The request must use exactly one entry point: provide channelID with checkType, or provide the full direct check configuration.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The Name of the organization |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dataCheckCreate](../schemas/dataCheckCreate/dataCheckCreate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[dataCheckResponse](../schemas/dataCheckResponse/dataCheckResponse.md)

