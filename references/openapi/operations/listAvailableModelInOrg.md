# GET /api/v1/organizations/{orgName}/llm/models

**Resource:** [llm](../resources/llm.md)
**List available model in org**
**Operation ID:** `listAvailableModelInOrg`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema** (inline):

Array

