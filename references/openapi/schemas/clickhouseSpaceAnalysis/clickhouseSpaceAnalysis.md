# clickhouseSpaceAnalysis

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `collectedAt` | string | Yes | Collection time in RFC3339 UTC. |
| `status` | string | Yes | success when all sources were collected, partial when at least one best-effort source failed. |
| `database` | string | No | Database filter applied to the collection, empty when all databases are included. |
| `summary` | [clickhouseSpaceSummary](clickhouseSpaceSummary.md) | No |  |
| `tables` | clickhouseTableSpace[] | Yes | Top tables ordered by physical bytes_on_disk. Totals are physical usage across all hosts, not deduplicated logical usage. |
| `partitions` | clickhousePartitionSpace[] | Yes | Top partitions ordered by physical bytes_on_disk. |
| `merges` | clickhouseMerge[] | Yes | In-progress background merges from system.merges ordered by elapsed time. |
| `mutations` | clickhouseMutation[] | Yes | Unfinished mutations from system.mutations ordered by creation time. |
| `sources` | clickhouseSource[] | Yes | Per-source collection status. |

