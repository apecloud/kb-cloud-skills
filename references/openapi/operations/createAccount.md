# POST /api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts

**Resource:** [rdbms](../resources/rdbms.md)
**Create cluster account**
**Operation ID:** `createAccount`

create an account in cluster

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes | name of the engine |
| `orgName` | path | string | Yes | name of the organization |
| `clusterName` | path | string | Yes | name of the cluster |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [account](../schemas/account/account.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | create redis account success |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[account](../schemas/account/account.md)

