# GET /admin/v1/data/dolphindb/organizations/{orgName}/clusters/{clusterName}/distribution

**Resource:** [dolphindb](../resources/dolphindb.md)
**DolphinDB GetDistribution**
**Operation ID:** `dolphinDBGetDistribution`

Filesystem bytes and physical chunk replica counts (including metadata/unready replicas). Not logical data size or healthy-copy counts.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Operation result |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[DolphinDBDistribution](../schemas/Dolphin/DolphinDBDistribution.md)

