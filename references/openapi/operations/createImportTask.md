# POST /api/v1/organizations/{orgName}/clusters/{clusterName}/import

**Resource:** [import](../resources/import.md)
**Create import task**
**Operation ID:** `createImportTask`

Creates new data import task based on data source configuration and import options

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | Organization name |
| `clusterName` | path | string | Yes | Cluster name |

## Request Body

Import task configuration including data source connection, object selection and import options

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [ImportTaskCreateRequest](../schemas/Import/ImportTaskCreateRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Task created successfully, returns basic task information |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |

**Success Response Schema:**

[ImportTaskResponse](../schemas/Import/ImportTaskResponse.md)

