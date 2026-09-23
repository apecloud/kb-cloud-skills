# modeServiceRefVersionCompatibility

Defines allowed source/ref service version combinations for a mode serviceRef.
Version patterns match semantic version segments, so "3", "3.0", and
"3.0.10" can match a whole major, minor, or patch family respectively.


**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `version` | string[] | No | Source cluster version patterns. Empty means all source versions.
 |
| `refVersion` | string[] | No | Referenced cluster version patterns. Empty means all referenced versions.
 |
| `message` | [localizedDescription](localizedDescription.md) | No |  |

