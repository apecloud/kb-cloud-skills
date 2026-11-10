# GET /api/v1/organizations/{orgName}/alerts/resource/{resourceType}/{resourceID}

**Resource:** [alertRule](../resources/alertRule.md)
**Get resource alert settings**
**Operation ID:** `getResourceAlertDisabled`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `resourceType` | path | alertResourceType | Yes | resourceType |
| `resourceID` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[alertCluster](../schemas/alertCluster/alertCluster.md)

