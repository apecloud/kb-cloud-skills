# POST /admin/v1/data/mongodb/organizations/{orgName}/clusters/{clusterName}/accounts

**Resource:** [mongodb](../resources/mongodb.md)
**Create mongodb account**
**Operation ID:** `createMongoDBAccount`

create an account in mongodb

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
| 201 | create redis account success |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[account](../schemas/account/account.md)

