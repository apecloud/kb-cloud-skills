# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/import/{id}

**Resource:** [import](../resources/import.md)
**Get import task details**
**Operation ID:** `getImportTask`

Gets detailed information about a specific import task by its ID

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | Organization name |
| `clusterName` | path | string | Yes | Cluster name |
| `id` | path | string | Yes | Import task ID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully returns import task details |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[ImportTaskResponse](../schemas/Import/ImportTaskResponse.md)

