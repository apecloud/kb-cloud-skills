# POST /api/v1/organizations/{orgName}/clusters/{clusterName}/rebuildInstance

**Resource:** [opsrequest](../resources/opsrequest.md)
**rebuild the instance**
**Operation ID:** `rebuildInstance`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the KubeBlocks cluster |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [opsRebuildInstance](../schemas/opsRebuildInstance/opsRebuildInstance.md)

## Responses

| Status | Description |
|--------|-------------|
| 202 | Accepted |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

