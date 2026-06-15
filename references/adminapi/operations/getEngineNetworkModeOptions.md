# GET /admin/v1/environments/{environmentName}/engineNetworkModes/options

**Resource:** [engine](../resources/engine.md)
**Get available network modes for all engines from engineOption config**
**Operation ID:** `getEngineNetworkModeOptions`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | environment name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[engineNetworkModeOptions](../schemas/engineNetworkModeOptions/engineNetworkModeOptions.md)

