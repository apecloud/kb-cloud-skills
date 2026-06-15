# DELETE /admin/v1/pricing

**Resource:** [pricing](../resources/pricing.md)
**Delete the environment pricing**
**Operation ID:** `deleteEnvironmentPricing`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | query | string | Yes | name of the environment |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when pricing deleted successfully. |
| 403 | (reference) |
| 404 | (reference) |

