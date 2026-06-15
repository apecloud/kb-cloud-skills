# POST /admin/v1/organizations/{orgName}/clusters/{clusterName}/logs/slow/explain

**Resource:** [clusterLog](../resources/clusterLog.md)
**Explain cluster slow log SQL**
**Operation ID:** `explainSlowLog`

Explain a concrete SQL from a slow log using the cluster default datasource.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [DmsExplainRequest](../schemas/Dms/DmsExplainRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful operation |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[clusterSlowLogExplainResponse](../schemas/clusterSlowLogExplainResponse/clusterSlowLogExplainResponse.md)

