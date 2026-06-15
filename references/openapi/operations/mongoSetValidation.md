# PUT /api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/databases/{db}/collections/{col}/validation

**Resource:** [dms](../resources/dms.md)
**set MongoDB collection validation options**
**Operation ID:** `mongoSetValidation`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `id` | path | string | Yes |  |
| `db` | path | string | Yes |  |
| `col` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [MongoSetValidationRequest](../schemas/Mongo/MongoSetValidationRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | validation updated |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

