# GET /api/v1/organizations/{orgName}/checks/{checkID}/sqlLogs

**Resource:** [dataReplication](../resources/dataReplication.md)
**Get Data Check SQL Logs**
**Operation ID:** `getDataCheckSQLLogs`

Read raw SQL lines emitted by check sql_logger entries.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The Name of the organization |
| `checkID` | path | string | Yes | The ID of the check |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Raw SQL lines. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

