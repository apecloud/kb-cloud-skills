# POST /api/v1/data/mongodb/organizations/{orgName}/clusters/{clusterName}/rbac/roles

**Resource:** [mongodb](../resources/mongodb.md)
**CreateRBACRole**
**Operation ID:** `mongoCreateRBACRole`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [MongoRBACRoleWrite](../schemas/Mongo/MongoRBACRoleWrite.md)

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

