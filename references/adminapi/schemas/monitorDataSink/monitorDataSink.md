# monitorDataSink

MonitorDataSink

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | MonitorDataSink ID |
| `exporterUrl` | string | Yes | url for exporter(eg. url for ElasticSearch) |
| `environmentID` | string | Yes | ID for relative Environment |
| `indexName` | string | No | indexName for ElasticSearch |
| `monitorDataSinkType` | string | Yes | type of monitor data sink(logs or metrics) |

