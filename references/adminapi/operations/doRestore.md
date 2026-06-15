# POST /admin/v1/organizations/{orgName}/clusters/{clusterName}/restore

**Resource:** [restore](../resources/restore.md)
**Restore current cluster or instance**
**Operation ID:** `doRestore`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the KubeBlocks cluster |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [restore](../schemas/restore/restore.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[restore](../schemas/restore/restore.md)

