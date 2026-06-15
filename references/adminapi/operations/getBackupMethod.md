# GET /admin/v1/organizations/{orgName}/{engineName}/clusterBackupMethod

**Resource:** [backupMethod](../resources/backupMethod.md)
**get backup method**
**Operation ID:** `getBackupMethod`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the org |
| `engineName` | path | string | Yes | engine name |
| `clusterID` | query | string | No | clusterID is required when you want to get the backup method of a existing cluster |
| `enablePITR` | query | boolean | No | define whether to enable PITR (Point-In-Time Recovery). This setting is required when clusterId is not empty. |
| `withRebuildInstance` | query | boolean | No | defined whether to search for rebuilding instance. |
| `withRestoreCluster` | query | boolean | No | defined whether to search for restoring cluster. |
| `withHScale` | query | boolean | No | defined whether to search for rebuilding instance. |
| `component` | query | string | No | The component type is required when withRebuildInstance/withHScale is true. |
| `mode` | query | string | No | The cluster mode, used to filter out unsupported backup methods. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

