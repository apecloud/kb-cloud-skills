# GET /admin/v1/instances

**Resource:** [instance](../resources/instance.md)
**List cluster instances**
**Operation ID:** `listInstances`
⚠️ **Deprecated**

List instances based on query parameters with constraints.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `envName` | query | string | No | Name of the environment (optional, required when querying by nodeName). |
| `nodeName` | query | string | No | Name of the node (optional, required when querying by envName). |
| `orgName` | query | string | No | Name of the organization (optional, required when querying by clusterName). |
| `clusterName` | query | string | No | Name of the cluster (optional). |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[instanceList](../schemas/instanceList/instanceList.md)

