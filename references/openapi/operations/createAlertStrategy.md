# POST /api/v1/organizations/{orgName}/alerts/strategies

**Resource:** [alertStrategy](../resources/alertStrategy.md)
**Create alert strategy in org**
**Operation ID:** `createAlertStrategy`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [alertStrategy](../schemas/alertStrategy/alertStrategy.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[alertStrategy](../schemas/alertStrategy/alertStrategy.md)

