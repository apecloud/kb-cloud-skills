# GET /admin/v1/organizations/{orgName}/cluster/{clusterName}/available-relations

**Resource:** [relation](../resources/relation.md)
**list the available clusters for the organization to create the a relation**
**Operation ID:** `listAvailableClustersForRelation`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `targetType` | query | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | list the available clusters for the organization to create the a relation successfully |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[availableClusterList](../schemas/availableClusterList/availableClusterList.md)

