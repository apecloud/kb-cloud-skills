# GET /api/v1/organizations/{orgName}/parent/{parentClusterID}/disasterRecovery

**Resource:** [disasterRecovery](../resources/disasterRecovery.md)
**List Disaster Recovery instances under the main cluster**
**Operation ID:** `listDisasterRecovery`

Retrieve a list of disaster recovery instances for a specific database cluster.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `parentClusterID` | path | string | Yes | The ID of the parent database cluster |
| `orgName` | path | string | Yes | name of the org |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A list of disaster recovery instances. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[disasterRecoveryClusterList](../schemas/disasterRecoveryClusterList/disasterRecoveryClusterList.md)

