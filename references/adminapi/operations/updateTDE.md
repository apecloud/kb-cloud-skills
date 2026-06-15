# POST /admin/v1/organizations/{orgName}/clusters/{clusterName}/tde

**Resource:** [cluster](../resources/cluster.md)
**Enable TDE**
**Operation ID:** `updateTDE`

Enable transparent data encryption for a cluster component. Disabling TDE is not supported.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the Cluster |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [tdeRequest](../schemas/tdeRequest/tdeRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[tdeResponse](../schemas/tdeResponse/tdeResponse.md)

