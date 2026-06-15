# GET /api/v1/features/{featureName}

**Resource:** [feature](../resources/feature.md)
**Get feature**
**Operation ID:** `readFeature`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `featureName` | path | string | Yes | name of the feature |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[feature](../schemas/feature/feature.md)

