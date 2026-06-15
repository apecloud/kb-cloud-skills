# GET /admin/v1/restoreTasks

**Resource:** [restore](../resources/restore.md)
**List restore tasks**
**Operation ID:** `listRestores`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | query | string | No | name of the Org |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[restoreList](../schemas/restoreList/restoreList.md)

