# PATCH /admin/v1/organizations/{orgName}/alerts/cluster/{clusterName}

**Resource:** [clusterAlertSwitch](../resources/clusterAlertSwitch.md)
**Set cluster alert disabled or enabled**
**Operation ID:** `setClusterAlertDisabled`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | clusterName |

## Request Body

**Content Types:** `application/json`

**Schema:** [alertCluster](../schemas/alertCluster/alertCluster.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[alertCluster](../schemas/alertCluster/alertCluster.md)

