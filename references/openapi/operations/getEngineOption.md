# GET /api/v1/engineOptions/{engineName}

**Resource:** [engineOption](../resources/engineOption.md)
**Get engineOption**
**Operation ID:** `getEngineOption`

Get a engineOption detail

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes | Name of the engineOption |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[engineOption](../schemas/engineOption/engineOption.md)

