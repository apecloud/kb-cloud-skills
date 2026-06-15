# DELETE /api/v1/organizations/{orgName}/clusters/{clusterName}/relation/{target}

**Resource:** [relation](../resources/relation.md)
**delete a existed relation between the clusters in the organization**
**Operation ID:** `deleteRelation`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `target` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | delete a existed relation between the clusters in the organization successfully |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

