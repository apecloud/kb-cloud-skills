# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/storageUsageHistory

**Resource:** [cluster](../resources/cluster.md)
**Get cluster storage usage history**
**Operation ID:** `getClusterStorageUsageHistory`

Get cluster storage usage history from backend-owned fixed metrics.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |
| `timeRange` | query | string | No | Requested history range. Supported values are 24h and 7d. Defaults to 24h. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[clusterStorageUsageHistory](../schemas/clusterStorageUsageHistory/clusterStorageUsageHistory.md)

