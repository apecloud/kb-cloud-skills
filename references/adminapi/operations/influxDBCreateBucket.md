# POST /admin/v1/data/influxdb/organizations/{orgName}/clusters/{clusterName}/buckets

**Resource:** [database](../resources/database.md)
**InfluxDB CreateBucket**
**Operation ID:** `influxDBCreateBucket`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [InfluxDBBucketCreate](../schemas/Influx/InfluxDBBucketCreate.md)

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

[InfluxDBBucket](../schemas/Influx/InfluxDBBucket.md)

