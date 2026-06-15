# PATCH /api/v1/organizations/{orgName}/clusters/{clusterName}/parameterTemplate

**Resource:** [parameterTemplate](../resources/parameterTemplate.md)
**Update cluster parameter template**
**Operation ID:** `updateClusterParameterTemplate`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [paramTpls](../schemas/paramTpls/paramTpls.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | update cluster parameter template successfully |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

