# POST /api/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/accounts

**Resource:** [kafka](../resources/kafka.md)
**Create cluster account**
**Operation ID:** `createKafkaAccount`

create an account in cluster

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
| 201 | create kafka account success |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |
| 501 | (reference) |

**Success Response Schema:**

[account](../schemas/account/account.md)

