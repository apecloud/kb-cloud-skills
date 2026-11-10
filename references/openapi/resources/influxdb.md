# influxdb

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v1/data/influxdb/organizations/{orgName}/clusters/{clusterName}/accounts` | InfluxDB ListUsers | [View](../operations/influxDBListUsers.md) |
| POST | `/api/v1/data/influxdb/organizations/{orgName}/clusters/{clusterName}/accounts` | InfluxDB CreateUser | [View](../operations/influxDBCreateUser.md) |
| DELETE | `/api/v1/data/influxdb/organizations/{orgName}/clusters/{clusterName}/accounts/{userID}` | InfluxDB DeleteUser | [View](../operations/influxDBDeleteUser.md) |
| PATCH | `/api/v1/data/influxdb/organizations/{orgName}/clusters/{clusterName}/accounts/{userID}/password` | InfluxDB ChangePassword | [View](../operations/influxDBChangePassword.md) |
| GET | `/api/v1/data/influxdb/organizations/{orgName}/clusters/{clusterName}/organizations` | InfluxDB ListOrganizations | [View](../operations/influxDBListOrganizations.md) |
| GET | `/api/v1/data/influxdb/organizations/{orgName}/clusters/{clusterName}/buckets` | InfluxDB ListBuckets | [View](../operations/influxDBListBuckets.md) |
| POST | `/api/v1/data/influxdb/organizations/{orgName}/clusters/{clusterName}/buckets` | InfluxDB CreateBucket | [View](../operations/influxDBCreateBucket.md) |
| GET | `/api/v1/data/influxdb/organizations/{orgName}/clusters/{clusterName}/buckets/{bucketID}` | InfluxDB GetBucket | [View](../operations/influxDBGetBucket.md) |
| DELETE | `/api/v1/data/influxdb/organizations/{orgName}/clusters/{clusterName}/buckets/{bucketID}` | InfluxDB DeleteBucket | [View](../operations/influxDBDeleteBucket.md) |
| PATCH | `/api/v1/data/influxdb/organizations/{orgName}/clusters/{clusterName}/buckets/{bucketID}` | InfluxDB UpdateBucket | [View](../operations/influxDBUpdateBucket.md) |
| GET | `/api/v1/data/influxdb/organizations/{orgName}/clusters/{clusterName}/accounts/{userID}/tokens` | InfluxDB ListTokens | [View](../operations/influxDBListTokens.md) |
| POST | `/api/v1/data/influxdb/organizations/{orgName}/clusters/{clusterName}/accounts/{userID}/tokens` | InfluxDB CreateToken | [View](../operations/influxDBCreateToken.md) |
| DELETE | `/api/v1/data/influxdb/organizations/{orgName}/clusters/{clusterName}/accounts/{userID}/tokens/{tokenID}` | InfluxDB DeleteToken | [View](../operations/influxDBDeleteToken.md) |
| PATCH | `/api/v1/data/influxdb/organizations/{orgName}/clusters/{clusterName}/accounts/{userID}/tokens/{tokenID}` | InfluxDB UpdateToken | [View](../operations/influxDBUpdateToken.md) |
