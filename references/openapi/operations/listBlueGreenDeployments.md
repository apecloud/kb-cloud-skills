# GET /api/v1/organizations/{orgName}/parent/{parentClusterID}/blueGreenDeployment

**Resource:** [blueGreenDeployment](../resources/blueGreenDeployment.md)
**List blue-green deployment instances for the specified parent cluster**
**Operation ID:** `listBlueGreenDeployments`

Retrieve a list of blue-green deployment instances associated with the given parent database cluster.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `parentClusterID` | path | string | Yes | The unique identifier of the parent database cluster |
| `orgName` | path | string | Yes | Name of the organization |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A list of blue-green deployment instances. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 501 | (reference) |

**Success Response Schema:**

[blueGreenDeploymentItemList](../schemas/blueGreenDeploymentItemList/blueGreenDeploymentItemList.md)

