# PUT /admin/v1/vulns

**Resource:** [vuln](../resources/vuln.md)
**Upload vulnerabilities**
**Operation ID:** `uploadVulns`

## Request Body

**Content Types:** `multipart/form-data`

**Schema:** [vulnUploadFormData](../schemas/vulnUploadFormData/vulnUploadFormData.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned when vulnerabilities are uploaded successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

