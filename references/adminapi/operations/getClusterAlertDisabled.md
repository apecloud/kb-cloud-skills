# GET /admin/v1/organizations/{orgName}/alerts/cluster/{clusterName}

**Resource:** [clusterAlertSwitch](../resources/clusterAlertSwitch.md)
**Check if cluster alert is disabled**
**Operation ID:** `getClusterAlertDisabled`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | clusterName |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[alertCluster](../schemas/alertCluster/alertCluster.md)

