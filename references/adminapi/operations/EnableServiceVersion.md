# POST /admin/v1/environments/{environmentName}/engines/{engineName}/serviceVersion

**Resource:** [enableServiceVersion](../resources/enableServiceVersion.md)
**enable the service version of the engine**
**Operation ID:** `EnableServiceVersion`

enable the service version of the engine and create related resources

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | environment name |
| `engineName` | path | string | Yes | Name of the engine |

## Request Body

**Required:** Yes

**Content Types:** `application/json`, `multipart/form-data`

**Schema** (inline):

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `serviceVersion` | string | No | The service version to enable |
| `engineVersion` | string | No | The engine version to enable |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema** (inline):

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `uploadId` | string | No | the id of the upload task |

