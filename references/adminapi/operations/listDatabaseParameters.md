# GET /admin/v1/databaseParameters

**Resource:** [databaseParameters](../resources/databaseParameters.md)
**List database parameters**
**Operation ID:** `listDatabaseParameters`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | query | string | No | engine Name |
| `component` | query | string | No | component type |

## Responses

| Status | Description |
|--------|-------------|
| 200 | list database parameters successfully |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[databaseParameterList](../schemas/databaseParameterList/databaseParameterList.md)

