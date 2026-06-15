# POST /admin/v1/engineOptions/{engineName}/release

**Resource:** [engineOption](../resources/engineOption.md)
**Release engineOption**
**Operation ID:** `releaseEngineOption`

Release a engineOption

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

