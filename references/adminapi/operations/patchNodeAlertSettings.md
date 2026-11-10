# PATCH /admin/v1/environments/{environmentName}/nodes/{nodeName}/alert/settings

**Resource:** [nodeAlert](../resources/nodeAlert.md)
**Update supplied node alert settings; omitted fields are preserved**
**Operation ID:** `patchNodeAlertSettings`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes |  |
| `nodeName` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [alertCluster](../schemas/alertCluster/alertCluster.md)

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

