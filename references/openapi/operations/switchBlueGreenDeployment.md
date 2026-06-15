# POST /api/v1/organizations/{orgName}/blueGreenDeployment/{deploymentID}/switch

**Resource:** [blueGreenDeployment](../resources/blueGreenDeployment.md)
**Switch roles of blue-green deployment instances**
**Operation ID:** `switchBlueGreenDeployment`

Switch the specified blue-green deployment cluster to act as the primary instance.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `deploymentID` | path | string | Yes | The unique identifier of the blue-green deployment cluster |
| `orgName` | path | string | Yes | Name of the organization |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Async job task information for the blue-green deployment switch operation. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 501 | (reference) |

**Success Response Schema:**

[blueGreenDeploymentSwitchResponse](../schemas/blueGreenDeploymentSwitchResponse/blueGreenDeploymentSwitchResponse.md)

