# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/import/preflight/{taskId}

**Resource:** [import](../resources/import.md)
**Get preflight task details**
**Operation ID:** `getImportPreflightTask`

Retrieves detailed information about a specific data import preflight task by its ID

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | Organization name |
| `clusterName` | path | string | Yes | Cluster name |
| `taskId` | path | string | Yes | Preflight task ID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully returns preflight task details |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[preCheckTaskDetail](../schemas/preCheckTaskDetail/preCheckTaskDetail.md)

