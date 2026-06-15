# DELETE /api/v1/data/mongodb/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}

**Resource:** [mongodb](../resources/mongodb.md)
**Delete mongodb account**
**Operation ID:** `deleteMongoDBAccount`

delete an account in mongodb

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the Cluster |
| `accountName` | path | string | Yes | name of the Cluster |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when project is deleted successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

