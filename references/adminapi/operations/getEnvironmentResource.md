# GET /admin/v1/environments/{environmentName}/resources/{resourceName}

**Resource:** [environment](../resources/environment.md)
**Get a live Kubernetes resource**
**Operation ID:** `getEnvironmentResource`

Returns one named Kubernetes object, excluding metadata.managedFields. The code allowlist permits v1 PersistentVolumeClaim, storage.k8s.io/v1 StorageClass and apelocal.csi.apecloud.com/v1alpha1 HostPathDefinition; other valid resource types return 403 before Kubernetes access. Requires Admin environment read permission. Does not support lists, subresources or writes.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes |  |
| `resourceName` | path | string | Yes |  |
| `apiVersion` | query | string | Yes | Kubernetes API version. Must match an explicitly allowed storage resource kind. |
| `kind` | query | string | Yes | Kubernetes kind. Allowed kinds are PersistentVolumeClaim, StorageClass and HostPathDefinition with their corresponding API versions. |
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

