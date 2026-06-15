# DELETE /api/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}

**Resource:** [kafka](../resources/kafka.md)
**Delete cluster account**
**Operation ID:** `deleteKafkaAccount`

delete an account in cluster

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the Cluster |
| `accountName` | path | string | Yes | name of the Cluster |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when account is deleted successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |
| 501 | (reference) |

