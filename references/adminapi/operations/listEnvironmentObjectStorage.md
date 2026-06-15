# POST /admin/v1/environmentObjectStorage

**Resource:** [environment](../resources/environment.md)
**List environment object storage**
**Operation ID:** `listEnvironmentObjectStorage`

## Request Body

**Content Types:** `application/json`

**Schema:** [kubeconfig](../schemas/kubeconfig/kubeconfig.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[environmentObjectStorage](../schemas/environmentObjectStorage/environmentObjectStorage.md)

