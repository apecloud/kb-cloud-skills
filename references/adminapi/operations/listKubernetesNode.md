# POST /admin/v1/kubernetes/nodes

**Resource:** [environment](../resources/environment.md)
**List Kubernetes nodes**
**Operation ID:** `listKubernetesNode`

List Kubernetes nodes before registered as environment

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `region` | query | string | No | region of Kubernetes node |
| `zone` | query | string | No | zone of Kubernetes node |
| `op` | query | listKubernetesNodeOpType | No | operation of this query, either in or notin |

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

[nodeList](../schemas/nodeList/nodeList.md)

