# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/databases/{db}/collections/{col}/validation

**Resource:** [dms](../resources/dms.md)
**get MongoDB collection validation options**
**Operation ID:** `mongoGetValidation`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `id` | path | string | Yes |  |
| `db` | path | string | Yes |  |
| `col` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |

**Success Response Schema:**

[MongoValidationInfo](../schemas/Mongo/MongoValidationInfo.md)

