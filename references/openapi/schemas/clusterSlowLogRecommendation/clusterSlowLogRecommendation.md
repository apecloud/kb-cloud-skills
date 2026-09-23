# clusterSlowLogRecommendation

A rule-based recommendation for a slow log diagnosis

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | string | No | Recommendation type. Current values are create_index, rewrite_sql, reduce_result_set, and investigate_lock. |
| `sql` | string | No |  |
| `description` | [clusterSlowLogLocalizedText](clusterSlowLogLocalizedText.md) | No |  |
| `source` | string | No | Evidence source used by the local rule |
| `safety` | string | No | Recommendation safety level. Current values are manual_review_required and safe_hint_only. |

