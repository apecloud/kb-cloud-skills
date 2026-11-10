# GET /api/v1/data/mongodb/organizations/{orgName}/clusters/{clusterName}/rbac/roles

**Resource:** [mongodb](../resources/mongodb.md)
**ListRBACRoles**
**Operation ID:** `mongoListRBACRoles`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `database` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Success |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

Array of [MongoRBACRole](../schemas/Mongo/MongoRBACRole.md)

