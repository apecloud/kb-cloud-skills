# POST /api/v1/organizations/{orgName}/clusters/{clusterName}/markClusterRestoreCompleted

**Resource:** [markCluster](../resources/markCluster.md)
**mark cluster to restore completed, usually used when manually repairing or recovering issues**
**Operation ID:** `markClusterRestoreCompleted`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the KubeBlocks cluster |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

