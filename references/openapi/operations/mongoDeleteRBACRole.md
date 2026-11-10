# DELETE /api/v1/data/mongodb/organizations/{orgName}/clusters/{clusterName}/rbac/roles/{database}/{roleName}

**Resource:** [mongodb](../resources/mongodb.md)
**DeleteRBACRole**
**Operation ID:** `mongoDeleteRBACRole`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `database` | path | string | Yes |  |
| `roleName` | path | string | Yes |  |
| `expectedRevision` | query | string | Yes |  |

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

