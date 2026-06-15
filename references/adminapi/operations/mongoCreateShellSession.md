# POST /admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/shell/sessions

**Resource:** [dms](../resources/dms.md)
**create MongoDB mongosh runtime session**
**Operation ID:** `mongoCreateShellSession`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |
| `id` | path | string | Yes | id of the datasource |

## Request Body

**Content Types:** `application/json`

**Schema:** [MongoShellCreateSessionRequest](../schemas/Mongo/MongoShellCreateSessionRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | shell session created |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |
| 503 | (reference) |

**Success Response Schema:**

[MongoShellSession](../schemas/Mongo/MongoShellSession.md)

