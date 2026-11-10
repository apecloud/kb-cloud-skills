# GET /admin/v1/data/mongodb/organizations/{orgName}/clusters/{clusterName}/rbac/roles/{database}/{roleName}

**Resource:** [mongodb](../resources/mongodb.md)
**GetRBACRole**
**Operation ID:** `mongoGetRBACRole`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `database` | path | string | Yes |  |
| `roleName` | path | string | Yes |  |

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

[MongoRBACRole](../schemas/Mongo/MongoRBACRole.md)

