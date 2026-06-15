# POST /admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/sqlExplain

**Resource:** [dms](../resources/dms.md)
**explain a SQL**
**Operation ID:** `sqlExplain`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |
| `id` | path | string | Yes | id of the datasource |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [DmsExplainRequest](../schemas/Dms/DmsExplainRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |

**Success Response Schema:**

[DmsQueryResponse](../schemas/Dms/DmsQueryResponse.md)

