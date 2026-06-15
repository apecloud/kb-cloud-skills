# vulnItem

a vulnerability which affected the cluster

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cveId` | string | Yes | the CVE ID of the vulnerability |
| `detail` | string | No | the detail of the vulnerability |
| `severity` | string | Yes | the severity of the vulnerability |
| `cvssVector` | string | No | the CVSS vector and score of the vulnerability |
| `publishedAt` | string (date-time) | Yes | the published time of the vulnerability |
| `modifiedAt` | string (date-time) | Yes | the modified time of the vulnerability |
| `refs` | refItem[] | No | the references of the vulnerability |

