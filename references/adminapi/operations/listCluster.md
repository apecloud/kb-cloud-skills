# GET /admin/v1/organizations/{orgName}/clusters

**Resource:** [cluster](../resources/cluster.md)
**List clusters in the Org**
**Operation ID:** `listCluster`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterDefinition` | query | string | No | The clusterDefinition in the List request |
| `environmentName` | query | string | No | Environment Type |
| `environmentType` | query | environmentType | No | Environment Type |
| `tagKey` | query | string | No | Tag key; this parameter is deprecated, use tagKeys instead |
| `tagValue` | query | string | No | Tag value; this parameter is deprecated, use tagValues instead |
| `tagKeys` | query | string[] | No | A list of tags' keys |
| `tagValues` | query | string[] | No | A list of tags' values corresponding to the tagKeys |
| `licenseId` | query | integer | No | license id |
| `refClusterName` | query | string | No | list clusters referenced by this cluster |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[clusterList](../schemas/clusterList/clusterList.md)

