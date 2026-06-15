# PUT /admin/v1/engineOptions/{engineName}

**Resource:** [engineOption](../resources/engineOption.md)
**Update engineOption**
**Operation ID:** `updateEngineOption`

Update a engineOption

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes | Name of the engine |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [engineOption](../schemas/engineOption/engineOption.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[engineOption](../schemas/engineOption/engineOption.md)

