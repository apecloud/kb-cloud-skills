# POST /admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/showData

**Resource:** [dms](../resources/dms.md)
**read data of table or view**
**Operation ID:** `showData`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |
| `id` | path | string | Yes | id of the datasource |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [ShowDataRequest](../schemas/Show/ShowDataRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |

**Success Response Schema:**

[DmsResult](../schemas/Dms/DmsResult.md)

