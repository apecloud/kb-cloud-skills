# POST /api/v1/organizations/{orgName}/clusters/{clusterName}/instances/{instanceName}/restart

**Resource:** [cluster](../resources/cluster.md)
**Restart instance of cluster**
**Operation ID:** `restartInstance`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the Cluster |
| `instanceName` | path | string | Yes | name of the instance |

## Responses

| Status | Description |
|--------|-------------|
| 204 | restart instance of cluster successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

