# POST /admin/v1/environments/{environmentName}/engineOptions

**Resource:** [engine](../resources/engine.md)
**Create environment engine option**
**Operation ID:** `createEnvironmentEngineOption`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | environment name |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [environmentEngineOptionCreate](../schemas/environmentEngineOptionCreate/environmentEngineOptionCreate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[environmentEngineOption](../schemas/environmentEngineOption/environmentEngineOption.md)

