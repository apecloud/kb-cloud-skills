# DELETE /api/v1/data/hive/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}

**Resource:** [hive](../resources/hive.md)
**Delete hive account**
**Operation ID:** `deleteHiveAccount`

delete an hive account in cluster

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the organization |
| `clusterName` | path | string | Yes | name of the cluster |
| `accountName` | path | string | Yes | name of the account |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when account is deleted successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

