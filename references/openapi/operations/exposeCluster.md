# POST /api/v1/organizations/{orgName}/clusters/{clusterName}/expose

**Resource:** [opsrequest](../resources/opsrequest.md)
**Expose cluster loadbalancer endpoint**
**Operation ID:** `exposeCluster`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the KubeBlocks cluster |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [opsExpose](../schemas/opsExpose/opsExpose.md)

## Responses

| Status | Description |
|--------|-------------|
| 202 | Accepted |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

