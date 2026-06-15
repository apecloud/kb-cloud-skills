# POST /admin/v1/kubernetes/storageclasses

**Resource:** [environment](../resources/environment.md)
**List Kubernetes storageclass**
**Operation ID:** `listKubernetesStorageClass`

List Kubernetes storageclass before registered as environment

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [kubeconfig](../schemas/kubeconfig/kubeconfig.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[storageClassList](../schemas/storageClassList/storageClassList.md)

