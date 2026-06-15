# POST /admin/v1/organizations/{orgName}/clusters

**Resource:** [cluster](../resources/cluster.md)
**Create new cluster**
**Operation ID:** `createCluster`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [clusterCreate](../schemas/clusterCreate/clusterCreate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[cluster](../schemas/cluster/cluster.md)

