# POST /admin/v1/organizations/{orgName}/clusters/{clusterName}/updateDS

**Resource:** [dms](../resources/dms.md)
**update the datasource**
**Operation ID:** `updateDataSourceV2`

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

