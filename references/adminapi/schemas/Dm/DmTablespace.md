# DmTablespace

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | tablespace name |
| `users` | string | No | damengdb users belong to this tablespace |
| `files` | DmFile[] | Yes | the physical files of this tablespace |
| `allocatedSizeMB` | string | No | the total size already allocated of this tablespace, unit MB |
| `usedSizeMB` | string | No | the current used size of this tablespace, unit MB |
| `usedRatio` | string | No | the current used ratio of this tablespace |
| `autoExtend` | boolean | No | whether this tablespace auto extend |
| `maxSizeMB` | string | No | the max size can be allocated of this tablespace, unit MB |
| `usedRatioInMax` | string | No | the used ratio in the max allocated size of this tablespace |
| `status` | [tableSpaceStatus](tableSpaceStatus.md) | No |  |

