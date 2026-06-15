# blueGreenDeployment

Blue Green Deployment APIs

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v1/organizations/{orgName}/blueGreenDeployment/{deploymentID}` | Get a blue-green deployment instance | [View](../operations/getBlueGreenDeployment.md) |
| DELETE | `/api/v1/organizations/{orgName}/blueGreenDeployment/{deploymentID}` | Delete a blue-green deployment instance | [View](../operations/deleteBlueGreenDeployment.md) |
| GET | `/api/v1/organizations/{orgName}/parent/{parentClusterID}/blueGreenDeployment` | List blue-green deployment instances for the specified parent cluster | [View](../operations/listBlueGreenDeployments.md) |
| POST | `/api/v1/organizations/{orgName}/parent/{parentClusterID}/blueGreenDeployment` | Create a new blue-green deployment instance | [View](../operations/createBlueGreenDeployment.md) |
| GET | `/api/v1/organizations/{orgName}/blueGreenDeployment/{deploymentID}/switch` | Get blue-green deployment switch job detail | [View](../operations/getBlueGreenDeploymentSwitchDetail.md) |
| POST | `/api/v1/organizations/{orgName}/blueGreenDeployment/{deploymentID}/switch` | Switch roles of blue-green deployment instances | [View](../operations/switchBlueGreenDeployment.md) |
| POST | `/api/v1/organizations/{orgName}/parent/{parentClusterID}/blueGreenDeployment/precheck` | Run a precheck for blue-green deployment | [View](../operations/createBlueGreenDeploymentPreCheck.md) |
| GET | `/api/v1/organizations/{orgName}/blueGreenDeployment/precheck/{preCheckID}` | Get blue-green deployment precheck task detail | [View](../operations/getBlueGreenDeploymentPreCheckDetail.md) |
