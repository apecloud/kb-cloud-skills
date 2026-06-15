# GET /admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts

**Resource:** [rdbms](../resources/rdbms.md)
**List cluster accounts**
**Operation ID:** `listAccounts`

list accounts in cluster

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes | name of the engine |
| `orgName` | path | string | Yes | name of the organization |
| `clusterName` | path | string | Yes | name of the cluster |

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

