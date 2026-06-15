# PUT /admin/v1/environments/{environmentName}/engineOption/{id}

**Resource:** [engine](../resources/engine.md)
**Update environment engine option**
**Operation ID:** `updateEnvironmentEngineOption`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | environment name |
| `id` | path | string | Yes | engine environment engine option record id |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [environmentEngineOptionUpdate](../schemas/environmentEngineOptionUpdate/environmentEngineOptionUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[environmentEngineOption](../schemas/environmentEngineOption/environmentEngineOption.md)

