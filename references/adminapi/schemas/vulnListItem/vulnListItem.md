# vulnListItem

a vulnerability which affected the cluster

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cveId` | string | Yes | the CVE ID of the vulnerability |
| `engineName` | string | Yes | the engine name of the vulnerability |
| `productName` | string | Yes | the product name of the vulnerability |
| `versions` | string[] | Yes | the versions of the product which are affected by the vulnerability |
| `fixedVersions` | string[] | No | the fixed versions of the product which fixed the vulnerability |
| `affectedClusters` | affectedClusterItem[] | No | the clusters which are affected by the vulnerability |
| `detail` | string | No | the detail of the vulnerability |
| `severity` | string | Yes | the severity of the vulnerability |
| `cvssVector` | string | No | the CVSS vector and score of the vulnerability |
| `publishedAt` | string (date-time) | Yes | the published time of the vulnerability |
| `modifiedAt` | string (date-time) | Yes | the modified time of the vulnerability |
| `refs` | refItem[] | No | the references of the vulnerability |

