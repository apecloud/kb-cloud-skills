# PATCH /admin/v1/organizations/{orgName}/clusters/{clusterName}

**Resource:** [cluster](../resources/cluster.md)
**Update cluster specified fields**
**Operation ID:** `patchCluster`

Update the specified Cluster

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the KubeBlocks cluster |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [clusterUpdate](../schemas/clusterUpdate/clusterUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned when project is updated successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[cluster](../schemas/cluster/cluster.md)

