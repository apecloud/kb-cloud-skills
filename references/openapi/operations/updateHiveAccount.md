# PATCH /api/v1/data/hive/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}

**Resource:** [hive](../resources/hive.md)
**update hive account**
**Operation ID:** `updateHiveAccount`

update an hive account in cluster

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
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
| 500 | (reference) |

