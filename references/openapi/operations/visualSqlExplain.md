# POST /api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/sqlExplain/visual

**Resource:** [dms](../resources/dms.md)
**explain a SQL as a normalized visual execution plan**
**Operation ID:** `visualSqlExplain`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |
| `id` | path | string | Yes | id of the datasource |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [DmsVisualExplainRequest](../schemas/Dms/DmsVisualExplainRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |

**Success Response Schema:**

[DmsExecutionPlanResult](../schemas/Dms/DmsExecutionPlanResult.md)

