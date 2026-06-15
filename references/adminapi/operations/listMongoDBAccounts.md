# GET /admin/v1/data/mongodb/organizations/{orgName}/clusters/{clusterName}/accounts

**Resource:** [mongodb](../resources/mongodb.md)
**List mongodb accounts**
**Operation ID:** `listMongoDBAccounts`

list accounts in mongodb

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the Cluster |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Success |
| 204 | Returned when project is deleted successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[accountList](../schemas/accountList/accountList.md)

