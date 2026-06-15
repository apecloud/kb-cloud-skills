# GET /admin/v1/environments/{environmentName}/engineNetworkModes/supported

**Resource:** [engine](../resources/engine.md)
**Get supported network modes for engine+mode from engineOption config**
**Operation ID:** `getEngineNetworkModeSupported`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | environment name |
| `engineName` | query | string | Yes | engine name |
| `mode` | query | string | Yes | engine mode |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[engineNetworkModeSupported](../schemas/engineNetworkModeSupported/engineNetworkModeSupported.md)

