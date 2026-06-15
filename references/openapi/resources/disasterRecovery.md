# disasterRecovery

Cluster Disaster Recovery APIs

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| DELETE | `/api/v1/organizations/{orgName}/disasterRecovery` | Delete a disaster recovery instance | [View](../operations/deleteDisasterRecovery.md) |
| GET | `/api/v1/organizations/{orgName}/parent/{parentClusterID}/disasterRecovery` | List Disaster Recovery instances under the main cluster | [View](../operations/listDisasterRecovery.md) |
| POST | `/api/v1/organizations/{orgName}/parent/{parentClusterID}/disasterRecovery` | Create a new disaster recovery instance | [View](../operations/createDisasterRecovery.md) |
| POST | `/api/v1/organizations/{orgName}/disasterRecovery/{clusterID}/promote` | Promote a disaster recovery instance to the main instance | [View](../operations/promoteDisasterRecovery.md) |
| GET | `/api/v1/organizations/{orgName}/disasterRecovery/{clusterID}/switchHistory` | Get switch history of a disaster recovery instance | [View](../operations/getDisasterRecoveryHistory.md) |
| GET | `/api/v1/organizations/{orgName}/disasterRecovery/{clusterID}/status` | Retrieve Disaster Recovery Instance Status | [View](../operations/getDisasterRecoveryStatus.md) |
