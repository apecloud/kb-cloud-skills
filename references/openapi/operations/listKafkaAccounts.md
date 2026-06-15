# GET /api/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/accounts

**Resource:** [kafka](../resources/kafka.md)
**List cluster accounts**
**Operation ID:** `listKafkaAccounts`

list accounts in cluster

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the Cluster |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Success |
| 204 | Returned when list accounts successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |
| 501 | (reference) |

**Success Response Schema:**

[accountList](../schemas/accountList/accountList.md)

