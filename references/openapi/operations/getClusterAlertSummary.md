# GET /api/v1/organizations/{orgName}/alerts/cluster/{clusterName}/summary

**Resource:** [alertObject](../resources/alertObject.md)
**Get cluster alert summary**
**Operation ID:** `getClusterAlertSummary`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |
| `status` | query | string | No | alert status filter, defaults to firing |
| `severity` | query | string | No | alert severity filter |
| `limit` | query | integer | No | max number of top alerts returned |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[clusterAlertSummary](../schemas/clusterAlertSummary/clusterAlertSummary.md)

