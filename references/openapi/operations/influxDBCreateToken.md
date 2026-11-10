# POST /api/v1/data/influxdb/organizations/{orgName}/clusters/{clusterName}/accounts/{userID}/tokens

**Resource:** [influxdb](../resources/influxdb.md)
**InfluxDB CreateToken**
**Operation ID:** `influxDBCreateToken`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `userID` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [InfluxDBTokenCreate](../schemas/Influx/InfluxDBTokenCreate.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Success |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[InfluxDBTokenCreated](../schemas/Influx/InfluxDBTokenCreated.md)

