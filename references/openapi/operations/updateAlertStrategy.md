# PATCH /api/v1/organizations/{orgName}/alerts/strategies/{strategyId}

**Resource:** [alertStrategy](../resources/alertStrategy.md)
**Update alert strategy**
**Operation ID:** `updateAlertStrategy`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `strategyId` | path | string | Yes | id of the alert strategies |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [alertStrategy](../schemas/alertStrategy/alertStrategy.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when project is deleted successfully. |
| 403 | (reference) |
| 404 | (reference) |

