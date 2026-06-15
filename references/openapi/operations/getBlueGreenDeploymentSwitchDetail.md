# GET /api/v1/organizations/{orgName}/blueGreenDeployment/{deploymentID}/switch

**Resource:** [blueGreenDeployment](../resources/blueGreenDeployment.md)
**Get blue-green deployment switch job detail**
**Operation ID:** `getBlueGreenDeploymentSwitchDetail`

Retrieve detailed information about the switch-over operation for a blue-green deployment cluster.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `deploymentID` | path | string | Yes | The unique identifier of the blue-green deployment instance |
| `orgName` | path | string | Yes | Name of the organization |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Details of the blue-green deployment switch job/task. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 501 | (reference) |

**Success Response Schema:**

[blueGreenDeploymentSwitchResponse](../schemas/blueGreenDeploymentSwitchResponse/blueGreenDeploymentSwitchResponse.md)

