# GET /admin/v1/platformComponents/{componentName}

**Resource:** [platformComponent](../resources/platformComponent.md)
**Get platform component detail**
**Operation ID:** `getPlatformComponent`

Get platform component detail by name, including monitoring and log query metadata

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `componentName` | path | string | Yes | Platform component name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[platformComponentDetails](../schemas/platformComponentDetails/platformComponentDetails.md)

