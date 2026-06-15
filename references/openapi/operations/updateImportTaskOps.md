# PATCH /api/v1/organizations/{orgName}/clusters/{clusterName}/import/{id}/ops/{opsType}

**Resource:** [import](../resources/import.md)
**Create a import task operation**
**Operation ID:** `updateImportTaskOps`

Performs pause or resume operation on import task based on opsType parameter

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | Organization name |
| `clusterName` | path | string | Yes | Cluster name |
| `id` | path | string | Yes | Import task ID |
| `opsType` | path | ImportOpsType | Yes | Operation type |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Import task operation completed successfully |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[ImportTaskResponse](../schemas/Import/ImportTaskResponse.md)

