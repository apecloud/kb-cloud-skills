# POST /admin/v1/organizations/{orgName}/clusters/{clusterName}/upgrade

**Resource:** [opsrequest](../resources/opsrequest.md)
**Upgrade cluster version**
**Operation ID:** `upgradeCluster`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the KubeBlocks cluster |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [opsUpgrade](../schemas/opsUpgrade/opsUpgrade.md)

## Responses

| Status | Description |
|--------|-------------|
| 202 | Accepted |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

