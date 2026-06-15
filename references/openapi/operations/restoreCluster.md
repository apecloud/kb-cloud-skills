# POST /api/v1/organizations/{orgName}/restore

**Resource:** [restore](../resources/restore.md)
**Restore new cluster**
**Operation ID:** `restoreCluster`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [restoreCreate](../schemas/restoreCreate/restoreCreate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[cluster](../schemas/cluster/cluster.md)

