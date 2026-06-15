# POST /api/v1/data/hive/organizations/{orgName}/clusters/{clusterName}/accounts

**Resource:** [hive](../resources/hive.md)
**Create Hive account**
**Operation ID:** `createHiveAccount`

create an hive account

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the Cluster |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [account](../schemas/account/account.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | create hive account success |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[account](../schemas/account/account.md)

