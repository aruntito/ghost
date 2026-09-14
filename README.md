# GHOST

**Discovery of unknown and orphaned infrastructure.**

> What exists that we do not know about?

GHOST explores methods for finding infrastructure that is unmanaged, forgotten, undocumented, disconnected from inventory, or otherwise absent from the expected system model.

## What it studies

- asset and service discovery
- orphan detection
- inventory reconciliation
- ownership gaps
- unknown dependency discovery
- evidence-backed infrastructure identity

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

## Status

Early research and architecture.

- [Architecture](docs/architecture.md)
- [Roadmap](docs/roadmap.md)

## License

MIT.