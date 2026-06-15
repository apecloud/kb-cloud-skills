# tpcc

tpcc is the tpcc benchmark object

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `step` | [benchmarkStep](benchmarkStep.md) | No |  |
| `limitCpu` | string | No | the cpu limit for test container |
| `limitMemory` | string | No | the memory limit for test container |
| `requestCpu` | string | No | the cpu request for test container |
| `requestMemory` | string | No | the memory request for test container |
| `name` | string | No | the name of benchmark |
| `cluster` | string | Yes | the cluster name |
| `database` | string | Yes | the database name |
| `username` | string | Yes | Username for database |
| `password` | string | Yes | Password for database |
| `address` | string | Yes | Address for database |
| `threads` | integer | No | Number of threads to use |
| `warehouses` | integer | No | Number of warehouses |
| `duration` | integer | No | the minutes of test duration |
| `limitTxPerMin` | integer | No | limit the number of transactions per minute, 0 means no limit |
| `newOrderWeight` | integer | No | Percentage of new order transactions |
| `paymentWeight` | integer | No | Percentage of payment transactions |
| `orderStatusWeight` | integer | No | Percentage of order status transactions |
| `deliveryWeight` | integer | No | Percentage of delivery transactions |
| `stockLevelWeight` | integer | No | Percentage of stock level transactions |
| `loadWorkers` | integer | No | number of parallel threads used to create initial content |
| `runTxnsPerTerminal` | integer | No | number of transactions to run per thread |
| `extraArgs` | string | No | Extra arguments for tpcc |

