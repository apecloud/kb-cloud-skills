# monitorDataSinkCreate

External Endpoint create option

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `exporterUrl` | string | Yes | url for exporter(eg. url for ElasticSearch) |
| `username` | string | No | Username |
| `environmentName` | string | Yes | Name for relative Environment |
| `monitorDataSinkType` | string | Yes | type of monitor data sink(logs or metrics) |
| `password` | string | No | Password |
| `apiKey` | string | No | apiKey |
| `indexName` | string | No | indexName for ElasticSearch |

