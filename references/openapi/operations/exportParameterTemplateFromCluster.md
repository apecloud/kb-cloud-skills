# POST /api/v1/organizations/{orgName}/clusters/{clusterName}/parameterTemplate

**Resource:** [parameterTemplate](../resources/parameterTemplate.md)
**Export parameter template from cluster**
**Operation ID:** `exportParameterTemplateFromCluster`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [paramTplCreateFromCluster](../schemas/paramTplCreateFromCluster/paramTplCreateFromCluster.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | export parameter template from cluster successfully |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

