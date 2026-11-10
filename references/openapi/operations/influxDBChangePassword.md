# PATCH /api/v1/data/influxdb/organizations/{orgName}/clusters/{clusterName}/accounts/{userID}/password

**Resource:** [influxdb](../resources/influxdb.md)
**InfluxDB ChangePassword**
**Operation ID:** `influxDBChangePassword`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `userID` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [InfluxDBPasswordChange](../schemas/Influx/InfluxDBPasswordChange.md)

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

