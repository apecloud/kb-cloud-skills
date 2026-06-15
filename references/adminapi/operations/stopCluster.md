# POST /admin/v1/organizations/{orgName}/clusters/{clusterName}/stop

**Resource:** [opsrequest](../resources/opsrequest.md)
**Stop cluster**
**Operation ID:** `stopCluster`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the KubeBlocks cluster |

## Request Body

**Content Types:** `application/json`

**Schema:** [opsStop](../schemas/opsStop/opsStop.md)

## Responses

| Status | Description |
|--------|-------------|
| 202 | Accepted |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

