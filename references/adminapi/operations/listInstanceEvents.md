# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/instances/{instanceName}/events

**Resource:** [cluster](../resources/cluster.md)
**List instance events**
**Operation ID:** `listInstanceEvents`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the KubeBlocks cluster |
| `instanceName` | path | string | Yes | name of the instance |
| `returnNumber` | query | integer (int32) | No | return number of events |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[instanceEventList](../schemas/instanceEventList/instanceEventList.md)

