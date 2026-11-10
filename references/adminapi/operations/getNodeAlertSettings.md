# GET /admin/v1/environments/{environmentName}/nodes/{nodeName}/alert/settings

**Resource:** [nodeAlert](../resources/nodeAlert.md)
**Get alert settings for a node in an environment**
**Operation ID:** `getNodeAlertSettings`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes |  |
| `nodeName` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Success |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[alertCluster](../schemas/alertCluster/alertCluster.md)

