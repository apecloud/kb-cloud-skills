# clusterSlowLogDiagnosis

Primary rule-based diagnosis card for a slow log EXPLAIN result

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `engine` | string | No | Diagnosis engine. Current value is rule_based. |
| `summary` | [clusterSlowLogLocalizedText](clusterSlowLogLocalizedText.md) | No |  |
| `primaryIssue` | [clusterSlowLogDiagnosisIssue](clusterSlowLogDiagnosisIssue.md) | No |  |
| `optimizationStrategy` | [clusterSlowLogLocalizedText](clusterSlowLogLocalizedText.md) | No |  |
| `recommendedAction` | [clusterSlowLogRecommendation](clusterSlowLogRecommendation.md) | No |  |
| `expectedBenefit` | string | No | Expected optimization benefit. Current values are unknown, low, medium, and high. |

