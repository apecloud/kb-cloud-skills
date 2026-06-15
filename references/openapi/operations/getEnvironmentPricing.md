# GET /api/v1/pricing

**Resource:** [pricing](../resources/pricing.md)
**Get the environment pricing**
**Operation ID:** `getEnvironmentPricing`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | query | string | No | name of the environment (if provided, returns a list with one item; if omitted, returns all environment prices) |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Retrieve the price of environment(s) as a list |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[environmentPricingList](../schemas/environmentPricingList/environmentPricingList.md)

