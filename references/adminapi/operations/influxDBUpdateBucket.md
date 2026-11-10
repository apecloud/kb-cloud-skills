# PATCH /admin/v1/data/influxdb/organizations/{orgName}/clusters/{clusterName}/buckets/{bucketID}

**Resource:** [database](../resources/database.md)
**InfluxDB UpdateBucket**
**Operation ID:** `influxDBUpdateBucket`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `bucketID` | path | string | Yes |  |
| `influxOrgID` | query | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [InfluxDBBucketUpdate](../schemas/Influx/InfluxDBBucketUpdate.md)

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

[InfluxDBBucket](../schemas/Influx/InfluxDBBucket.md)

