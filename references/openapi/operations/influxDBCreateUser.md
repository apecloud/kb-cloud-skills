# POST /api/v1/data/influxdb/organizations/{orgName}/clusters/{clusterName}/accounts

**Resource:** [influxdb](../resources/influxdb.md)
**InfluxDB CreateUser**
**Operation ID:** `influxDBCreateUser`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [InfluxDBUserCreate](../schemas/Influx/InfluxDBUserCreate.md)

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

[InfluxDBUser](../schemas/Influx/InfluxDBUser.md)

