# GET /api/v1/organizations/{orgName}/disasterRecovery/{clusterID}/status

**Resource:** [disasterRecovery](../resources/disasterRecovery.md)
**Retrieve Disaster Recovery Instance Status**
**Operation ID:** `getDisasterRecoveryStatus`

Get detailed information about the status of a specific disaster recovery instance, including delay and current replication point.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `clusterID` | path | string | Yes | Unique identifier of the disaster recovery instance |
| `orgName` | path | string | Yes | Name of the organization |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Status query successfully |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[disasterRecoveryStatusResponse](../schemas/disasterRecoveryStatusResponse/disasterRecoveryStatusResponse.md)

