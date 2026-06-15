# SLACluster

The cluster summary used by SLA calculation results. SLA responses can be built from historical outage data, so general cluster list fields may be unavailable.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No | ID of cluster. |
| `name` | string | No | Name of cluster. |
| `displayName` | string | No | Display name of cluster. |
| `orgName` | string | No | Org Name. |
| `environmentName` | string | No | Environment Name. |
| `engine` | string | No | Cluster Application Engine. |
| `clusterType` | [clusterType](clusterType.md) | No |  |
| `createdAt` | string (date-time) | No | The timestamp when the cluster was created, when available. |
| `status` | string | No | The SLA calculation status for the cluster. |
| `version` | string | No | Cluster Application Version. |

