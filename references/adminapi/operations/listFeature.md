# GET /admin/v1/features

**Resource:** [feature](../resources/feature.md)
**Get feature list**
**Operation ID:** `listFeature`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `group` | query | string | No | name of the feature group |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[featureList](../schemas/featureList/featureList.md)

