# PUT /api/v1/data/mongodb/organizations/{orgName}/clusters/{clusterName}/rbac/users/{database}/{username}/password

**Resource:** [mongodb](../resources/mongodb.md)
**ChangeRBACUserPassword**
**Operation ID:** `mongoChangeRBACUserPassword`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `database` | path | string | Yes |  |
| `username` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [MongoRBACPasswordChange](../schemas/Mongo/MongoRBACPasswordChange.md)

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

