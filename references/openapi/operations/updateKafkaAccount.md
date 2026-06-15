# PATCH /api/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}

**Resource:** [kafka](../resources/kafka.md)
**update cluster account**
**Operation ID:** `updateKafkaAccount`

update an account in cluster

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the Cluster |
| `accountName` | path | string | Yes | name of the account |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [account](../schemas/account/account.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | upadte kafka account success |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |
| 501 | (reference) |

**Success Response Schema:**

[account](../schemas/account/account.md)

