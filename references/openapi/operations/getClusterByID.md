# GET /api/v1/organizations/{orgName}/clustersWithDelete/{clusterID}

**Resource:** [cluster](../resources/cluster.md)
**Get cluster details by ID**
**Operation ID:** `getClusterByID`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterID` | path | string | Yes | ID of the KubeBlocks cluster |
| `backupName` | query | string | No | Backup name to override cluster components from its snapshot |
| `restoreTime` | query | string | No | Restore time to find latest continuous backup snapshot after this time |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |

**Success Response Schema:**

[cluster](../schemas/cluster/cluster.md)

