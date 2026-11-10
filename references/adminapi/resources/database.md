# database

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/admin/v1/data/influxdb/organizations/{orgName}/clusters/{clusterName}/buckets` | InfluxDB CreateBucket | [View](../operations/influxDBCreateBucket.md) |
| GET | `/admin/v1/data/influxdb/organizations/{orgName}/clusters/{clusterName}/buckets/{bucketID}` | InfluxDB GetBucket | [View](../operations/influxDBGetBucket.md) |
| DELETE | `/admin/v1/data/influxdb/organizations/{orgName}/clusters/{clusterName}/buckets/{bucketID}` | InfluxDB DeleteBucket | [View](../operations/influxDBDeleteBucket.md) |
| PATCH | `/admin/v1/data/influxdb/organizations/{orgName}/clusters/{clusterName}/buckets/{bucketID}` | InfluxDB UpdateBucket | [View](../operations/influxDBUpdateBucket.md) |
| GET | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/databases` | List cluster databases | [View](../operations/listDatabases.md) |
| POST | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/databases` | Create cluster database | [View](../operations/createDatabase.md) |
| GET | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/databases/{databaseName}` |  | [View](../operations/getDatabase.md) |
| DELETE | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/databases/{databaseName}` | Delete cluster database | [View](../operations/deleteDatabase.md) |
| PATCH | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/databases/{databaseName}` | update database config | [View](../operations/updateDatabaseConfig.md) |
