# POST /admin/v1/organizations/{orgName}/clusters/{clusterName}/relations

**Resource:** [relation](../resources/relation.md)
**create a relation between the clusters in the organization**
**Operation ID:** `createRelation`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `target` | query | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | create a relation between the clusters in the organization successfully |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

