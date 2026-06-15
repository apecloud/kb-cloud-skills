# GET /admin/v1/environments/{environmentName}/engines/{engineName}/imageUploadProgress

**Resource:** [serviceVersion](../resources/serviceVersion.md)
**get the progress of uploading image task**
**Operation ID:** `GetUploadImageProgress`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | environment name |
| `engineName` | path | string | Yes | Name of the engine |
| `uploadId` | query | string | Yes | upload id |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema** (inline):

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `uploadId` | string | No | the id of the upload task |
| `imageName` | string | No | the name of the uploaded image |
| `status` | string | No | the status of the upload task |
| `step` | string | No | the current step of the upload task |
| `percentage` | number | No | the percentage of the upload task |

