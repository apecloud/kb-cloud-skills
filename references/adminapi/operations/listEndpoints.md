# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/endpoints

**Resource:** [cluster](../resources/cluster.md)
**List cluster endpoints**
**Operation ID:** `listEndpoints`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the KubeBlocks cluster |
| `nodePortHostCount` | query | integer | No | count of the NodePort host |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[endpointList](../schemas/endpointList/endpointList.md)

