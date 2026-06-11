#FieldWorks#

An open source industrial AI framework. Protocol-first, plant-agnostic, runs on-premises.

FieldWorks gives industrial facilities a natural language interface to their own process data. Connect it to your existing protocol infrastructure, describe your plant, and operators can diagnose faults and query plant status in plain English. No cloud dependency. Air-gap ready.

##Repositories##
| Repo | Language | Description |
| --- | --- | --- |
| fieldworks-core | Python | Topology validation, specialist prompt generation, aggregator configuration |
| fieldworks-adapters | Rust | Conformant MCP protocol adapters — MQTT, OPC-UA, Modbus, DNP3, EtherNet/IP, AVEVA | 
| fieldworks-spec | — | Framework specification v0.1 | 
| fieldworks-site | — | fieldworks.build |

##Reference implementation##
waterworks-ai — a complete industrial AI deployment built on FieldWorks. Water treatment plant scenario, multi-agent diagnostics, reactive monitoring, four-store memory architecture.

##Status##
Active development. v0.1 in progress.

##License##
Apache 2.0
