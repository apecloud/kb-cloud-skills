# DELETE /api/v1/data/influxdb/organizations/{orgName}/clusters/{clusterName}/accounts/{userID}

**Resource:** [influxdb](../resources/influxdb.md)
**InfluxDB DeleteUser**
**Operation ID:** `influxDBDeleteUser`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `userID` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Success |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 500 | (reference) |

