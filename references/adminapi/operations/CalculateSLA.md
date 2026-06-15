# GET /admin/v1/sla

**Resource:** [SLA](../resources/SLA.md)
**Calculate SLA for a environment**
**Operation ID:** `CalculateSLA`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | query | string[] | No | name of the environment |
| `clusterID` | query | string[] | No | id of the cluster |
| `engine` | query | string[] | No | database engine type |
| `orgName` | query | string[] | No | name of the organization |
| `startTime` | query | integer (int64) | Yes | SLA calculation start time Unix timestamp, unit is second. |
| `endTime` | query | integer (int64) | Yes | SLA calculation end time Unix timestamp, unit is second. |
| `clusterNamePrefix` | query | string | No | Filter clusters by name prefix (fuzzy search). |
| `page` | query | integer (int32) | No | Page number for pagination, starts from 1. |
| `pageSize` | query | integer (int32) | No | Number of items per page. |
| `orderBy` | query | string | No | Order by field, available values are "clusterName", "engine". |
| `desc` | query | boolean | No | Whether to sort in descending order. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | SLA calculated successfully |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[ClustersSLA](../schemas/Clusters/ClustersSLA.md)

