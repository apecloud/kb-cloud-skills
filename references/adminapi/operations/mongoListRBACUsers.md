# GET /admin/v1/data/mongodb/organizations/{orgName}/clusters/{clusterName}/rbac/users

**Resource:** [mongodb](../resources/mongodb.md)
**ListRBACUsers**
**Operation ID:** `mongoListRBACUsers`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `database` | query | string | No |  |
| `allDatabases` | query | boolean | No | List accounts from all authentication databases. Overrides database; returns role memberships without effective privileges. Use the user detail endpoint for privileges. Requires viewUser and viewRole on the relevant databases. |

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

Array of [MongoRBACUser](../schemas/Mongo/MongoRBACUser.md)

