[comment]: <> (Code generated by mdatagen. DO NOT EDIT.)

# process

## Metrics

These are the metrics available for this scraper.

| Name | Description | Unit | Type | Attributes |
| ---- | ----------- | ---- | ---- | ---------- |
| process.cpu.time | Total CPU seconds broken down by different states. | s | Sum | <ul> <li>state</li> </ul> |
| process.disk.io | Disk bytes transferred. | By | Sum | <ul> <li>direction</li> </ul> |
| process.memory.physical_usage | The amount of physical memory in use. | By | Sum | <ul> </ul> |
| process.memory.virtual_usage | Virtual memory size. | By | Sum | <ul> </ul> |

## Attributes

| Name | Description |
| ---- | ----------- |
| direction | Direction of flow of bytes (read or write). |
| state | Breakdown of CPU usage by type. |
