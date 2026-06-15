# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/haHistory

**Resource:** [cluster](../resources/cluster.md)
**describe cluster HA history**
**Operation ID:** `describeClusterHaHistory`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the KubeBlocks cluster |
| `componentName` | query | string | No | name of the component |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Accepted |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[haHistoryList](../schemas/haHistoryList/haHistoryList.md)

