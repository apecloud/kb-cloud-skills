# PATCH /admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}

**Resource:** [rdbms](../resources/rdbms.md)
**update cluster account**
**Operation ID:** `updateAccount`

update an account in cluster

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes | name of the engine |
| `orgName` | path | string | Yes | name of the organization |
| `clusterName` | path | string | Yes | name of the cluster |
| `accountName` | path | string | Yes | name of the account |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [account](../schemas/account/account.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Update account password successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

