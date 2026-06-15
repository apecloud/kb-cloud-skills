# DELETE /api/v1/organizations/{orgName}/clusters/{clusterName}/import/{id}

**Resource:** [import](../resources/import.md)
**Delete import task**
**Operation ID:** `deleteImportTask`

Stops and deletes specified import task, will clean up related Kubernetes resources

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | Organization name |
| `clusterName` | path | string | Yes | Cluster name |
| `id` | path | string | Yes | Import task ID |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Task deleted successfully |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

