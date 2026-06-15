# POST /api/v1/organizations/{orgName}/clusters/{clusterName}/promote

**Resource:** [opsrequest](../resources/opsrequest.md)
**Promote cluster intance to primary**
**Operation ID:** `promoteCluster`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the KubeBlocks cluster |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [opsPromote](../schemas/opsPromote/opsPromote.md)

## Responses

| Status | Description |
|--------|-------------|
| 202 | Accepted |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

