# FieldWorks

An open source industrial AI framework. Protocol-first, plant-agnostic, runs on-premises.

FieldWorks gives industrial facilities a natural language interface to their own process data. Connect it to your existing protocol infrastructure, describe your plant, and operators can diagnose faults and query plant status in plain English. No cloud dependency. Air-gap ready.

## Repositories
| Repo | Language | Description |
| --- | --- | --- |
| [fieldworks-core](https://github.com/fieldworks-build/fieldworks-core) | Python | Topology validation, specialist prompt generation, aggregator configuration |
| [fieldworks-adapters](https://github.com/fieldworks-build/fieldworks-adapters) | Rust | Conformant MCP protocol adapters — MQTT, OPC-UA, Modbus, DNP3, EtherNet/IP, AVEVA | 
| [fieldworks-examples](https://github.com/fieldworks-build/fieldworks-examples) | Python, Rust | Dependency-free examples for the Fieldworks industrial AI framework |
| [fieldworks-spec](https://github.com/fieldworks-build/fieldworks-spec/blob/main/Fieldworks_Framework_Specification_v0.1.pdf) |  | Framework specification v0.1 | 

## Reference implementation
[waterworks-ai](https://github.com/smslavin/waterworks-ai) — a complete industrial AI deployment built on FieldWorks. Water treatment plant scenario, multi-agent diagnostics, reactive monitoring, four-store memory architecture.

## Status
Active development. v0.1 in progress.

## License
Apache 2.0
