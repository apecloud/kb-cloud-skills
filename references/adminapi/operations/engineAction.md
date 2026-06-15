# POST /admin/v1/environments/{environmentName}/engines/{engineName}

**Resource:** [engine](../resources/engine.md)
**Manage engine in environment**
**Operation ID:** `engineAction`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the EnvironmentName |
| `engineName` | path | string | Yes | name of the engine |

## Request Body

Request body for engine operations

**Required:** Yes

**Content Types:** `application/json`

**Schema** (inline):

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `version` | string | No | Version of the engine, required for upgrade/enable/disable action |
| `action` | [engineActionType](../schemas/engineActionType/engineActionType.md) | No |  |
| `id` | string | No | The engine id to action |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Operation completed successfully |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

