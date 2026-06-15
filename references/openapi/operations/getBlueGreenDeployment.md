# GET /api/v1/organizations/{orgName}/blueGreenDeployment/{deploymentID}

**Resource:** [blueGreenDeployment](../resources/blueGreenDeployment.md)
**Get a blue-green deployment instance**
**Operation ID:** `getBlueGreenDeployment`

Retrieve details for a single blue-green deployment instance by parent cluster and organization.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `deploymentID` | path | string | Yes | The unique identifier of the blue-green deployment instance |
| `orgName` | path | string | Yes | Name of the organization |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Details of the blue-green deployment instance. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 501 | (reference) |

**Success Response Schema:**

[blueGreenDeploymentItem](../schemas/blueGreenDeploymentItem/blueGreenDeploymentItem.md)

