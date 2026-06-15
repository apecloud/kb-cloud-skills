# POST /admin/v1/organizations/{orgName}/clusters/{clusterName}/vscale

**Resource:** [opsrequest](../resources/opsrequest.md)
**Vertical scale cluster**
**Operation ID:** `verticalScaleCluster`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the KubeBlocks cluster |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [opsVScale](../schemas/opsVScale/opsVScale.md)

## Responses

| Status | Description |
|--------|-------------|
| 202 | Accepted |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

