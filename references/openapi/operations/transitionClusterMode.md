# POST /api/v1/organizations/{orgName}/clusters/{clusterName}/modeTransition

**Resource:** [cluster](../resources/cluster.md)
**Transition cluster engine mode**
**Operation ID:** `transitionClusterMode`

Validates the mode transition, updates the cluster spec, and creates an hscale task when required. Returns the resulting OpsRequest name and task ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the KubeBlocks cluster |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [clusterModeTransition](../schemas/clusterModeTransition/clusterModeTransition.md)

## Responses

| Status | Description |
|--------|-------------|
| 202 | Mode transition accepted. Returns the OpsRequest name and task ID when an hscale operation is created. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

