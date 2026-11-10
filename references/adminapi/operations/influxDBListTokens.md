# GET /admin/v1/data/influxdb/organizations/{orgName}/clusters/{clusterName}/accounts/{userID}/tokens

**Resource:** [influxdb](../resources/influxdb.md)
**InfluxDB ListTokens**
**Operation ID:** `influxDBListTokens`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `userID` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Success |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

Array of [InfluxDBToken](../schemas/Influx/InfluxDBToken.md)

