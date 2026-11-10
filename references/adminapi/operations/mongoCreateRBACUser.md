# POST /admin/v1/data/mongodb/organizations/{orgName}/clusters/{clusterName}/rbac/users

**Resource:** [mongodb](../resources/mongodb.md)
**CreateRBACUser**
**Operation ID:** `mongoCreateRBACUser`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [MongoRBACUserCreate](../schemas/Mongo/MongoRBACUserCreate.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Success |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 500 | (reference) |

