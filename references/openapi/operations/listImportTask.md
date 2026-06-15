# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/import

**Resource:** [import](../resources/import.md)
**Query import task list**
**Operation ID:** `listImportTask`

Gets import task list for specified cluster, supports filtering by status and pagination

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | Organization name |
| `clusterName` | path | string | Yes | Cluster name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully returns task list with pagination info |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[ImportTaskListResponse](../schemas/Import/ImportTaskListResponse.md)

