# POST /api/v1/organizations/{orgName}/clusters/{clusterName}/createDS

**Resource:** [dms](../resources/dms.md)
**create the datasource**
**Operation ID:** `createDataSourceV2`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [datasource](../schemas/datasource/datasource.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |

**Success Response Schema:**

[datasource](../schemas/datasource/datasource.md)

