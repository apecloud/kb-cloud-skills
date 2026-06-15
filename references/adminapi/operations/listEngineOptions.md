# GET /admin/v1/engineOptions

**Resource:** [engineOption](../resources/engineOption.md)
**List all engineOptions**
**Operation ID:** `listEngineOptions`

list all engineOptions

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `version` | query | engineOptionVersion | No | The version of the engineOption to query, `current` from potentially modified data, `original` from the json files of the apiserver |
| `filterLoadBackupFromOfflineInstance` | query | boolean | No | Whether to filter load backup from offline instance |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[engineOptionList](../schemas/engineOptionList/engineOptionList.md)

