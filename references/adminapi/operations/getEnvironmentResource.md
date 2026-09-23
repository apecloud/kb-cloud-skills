# GET /admin/v1/environments/{environmentName}/resources/{resourceName}

**Resource:** [environment](../resources/environment.md)
**Get a live Kubernetes resource**
**Operation ID:** `getEnvironmentResource`

Returns one named Kubernetes object, excluding metadata.managedFields. The code allowlist currently permits only apiVersion v1 with kind PersistentVolumeClaim; other valid resource types return 403 before Kubernetes access. Requires Admin environment read permission. Does not support lists, subresources or writes.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes |  |
| `resourceName` | path | string | Yes |  |
| `apiVersion` | query | string | Yes | Kubernetes API version. Currently only v1 with kind PersistentVolumeClaim is allowed. |
| `kind` | query | string | Yes | Kubernetes kind. Currently only PersistentVolumeClaim with apiVersion v1 is allowed. |
| `namespace` | query | string | No | Required for namespaced kinds; must be omitted for cluster-scoped kinds. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The live Kubernetes resource, including metadata, spec and status when present. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[jsonBody](../schemas/jsonBody/jsonBody.md)

