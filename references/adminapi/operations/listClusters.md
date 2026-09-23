# GET /admin/v1/clusters

**Resource:** [cluster](../resources/cluster.md)
**Get cluster list**
**Operation ID:** `listClusters`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | query | string | No | Organization name, if envName is provided, orgName is required |
| `envName` | query | string | No | Environment name |
| `withStatic` | query | boolean | No | Whether to include static clusters |
| `endpointHost` | query | string | No | Case-insensitive substring to match against the host part of cached cluster endpoints |
| `includeEndpoints` | query | boolean | No | Whether to include cached user-visible endpoints in each cluster item |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[clusterList](../schemas/clusterList/clusterList.md)

