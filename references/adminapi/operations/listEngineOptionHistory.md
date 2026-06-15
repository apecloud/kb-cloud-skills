# GET /admin/v1/engineOptionHistories

**Resource:** [engineOption](../resources/engineOption.md)
**List engineOption history**
**Operation ID:** `listEngineOptionHistory`

List a engineOption histories of a engine

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | query | string | Yes | Name of the engine |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[engineOptionHistoryList](../schemas/engineOptionHistoryList/engineOptionHistoryList.md)

