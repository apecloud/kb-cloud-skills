# POST /api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/query

**Resource:** [dms](../resources/dms.md)
**create a SQL query**
**Operation ID:** `query`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |
| `id` | path | string | Yes | id of the datasource |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [DmsQueryRequest](../schemas/Dms/DmsQueryRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |

**Success Response Schema:**

[DmsQueryResponse](../schemas/Dms/DmsQueryResponse.md)

