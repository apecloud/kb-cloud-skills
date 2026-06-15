# GET /admin/v1/environments/{environmentName}/nodes/{nodeName}/pods

**Resource:** [environment](../resources/environment.md)
**List Pod in the environment node**
**Operation ID:** `listNodePod`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |
| `nodeName` | path | string | Yes | name of the environment node |
| `type` | query | string | Yes | filter Pods by type, supported types [all, kube-system, kb-system, cluster], default all if not provided |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Success |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[listBody](../schemas/listBody/listBody.md)

