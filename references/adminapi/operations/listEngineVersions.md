# GET /admin/v1/engineVersions/{engineName}

**Resource:** [engine](../resources/engine.md)
**Get engine version list**
**Operation ID:** `listEngineVersions`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes | Name of Engine. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[engineVersionList](../schemas/engineVersionList/engineVersionList.md)

