# GHOST

**Discovery of unknown and orphaned infrastructure.**

> What exists that we do not know about?

GHOST explores methods for finding infrastructure that is unmanaged, forgotten, undocumented, disconnected from inventory, or otherwise absent from the expected system model.

## Why it exists

A topology is only as trustworthy as the infrastructure it knows about.

GHOST focuses on the gap between **what the system believes exists** and **what evidence suggests actually exists**. Unknown infrastructure is treated as an investigation target, not silently classified.

## What it studies

- asset and service discovery
- orphan detection
- inventory reconciliation
- ownership gaps
- unknown dependency discovery
- evidence-backed infrastructure identity

## Use cases

| Use case | Question answered |
| --- | --- |
| Asset discovery | What exists outside the expected inventory? |
| Inventory reconciliation | Which records disagree with observed reality? |
| Orphan detection | Which resources have unclear ownership? |
| Dependency discovery | What unknown relationship may affect the topology? |
| Ownership research | Where are accountability gaps? |

## Architecture

```text
OBSERVATIONS + INVENTORY + NETWORK SIGNALS
                    │
                    ▼
              ENTITY DISCOVERY
                    │
                    ▼
             IDENTITY MATCHING
                    │
              ┌─────┴─────┐
              ▼           ▼
           KNOWN       UNKNOWN
              │           │
              └─────┬─────┘
                    ▼
             DISCOVERY REPORT
                    │
                    ▼
                  GRID
```

## Ecosystem

GHOST feeds discovered infrastructure into GRID and improves the context available to the incident and recovery systems.

## Design principle

**Unknown does not automatically mean malicious.** The system should preserve evidence, uncertainty, inventory conflicts, and ownership gaps rather than inventing certainty.

## Status

Early research and architecture.

- [Architecture](docs/architecture.md)
- [Roadmap](docs/roadmap.md)

## License

MIT.