# pageResult

PageResult info

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `first` | string | No | a link to the first page of results. This link is optional for collections that cannot be indexed directly to a given page |
| `last` | string | No | a link to the last page of results. This link is optional for collections that cannot be indexed directly to a given page |
| `next` | string | No | a link to the next page of results. A response that does not contain a next link does not have further data to fetch |
| `prev` | string | No | a link to the previous page of results. A response that does not contain a prev link has no previous data. This link is optional for collections that cannot be traversed backward |
| `totalSize` | integer (int64) | No | the total count of items in the list irrespective of pagination |

