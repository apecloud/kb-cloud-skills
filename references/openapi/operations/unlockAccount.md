# PATCH /api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/unlock

**Resource:** [rdbms](../resources/rdbms.md)
**Unlock cluster account**
**Operation ID:** `unlockAccount`

unlock an account in cluster

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes | name of the engine |
| `orgName` | path | string | Yes | name of the organization |
| `clusterName` | path | string | Yes | name of the cluster |
| `accountName` | path | string | Yes | name of the account |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when account is unlocked successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

