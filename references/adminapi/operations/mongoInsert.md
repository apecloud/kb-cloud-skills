# POST /admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/databases/{db}/collections/{col}/insert

**Resource:** [dms](../resources/dms.md)
**insert MongoDB document(s)**
**Operation ID:** `mongoInsert`

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

**Schema:** [MongoInsertRequest](../schemas/Mongo/MongoInsertRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |

**Success Response Schema:**

[MongoWriteResponse](../schemas/Mongo/MongoWriteResponse.md)

