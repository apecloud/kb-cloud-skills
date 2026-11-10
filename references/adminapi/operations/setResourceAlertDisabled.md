# PATCH /admin/v1/organizations/{orgName}/alerts/resource/{resourceType}/{resourceID}

**Resource:** [alertRule](../resources/alertRule.md)
**Update resource alert settings**
**Operation ID:** `setResourceAlertDisabled`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `resourceType` | path | alertResourceType | Yes | resourceType |
| `resourceID` | path | string | Yes |  |

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

