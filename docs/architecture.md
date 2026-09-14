# GHOST Architecture

GHOST discovers infrastructure that is missing from expected inventory or topology.

## Flow

```text
OBSERVATIONS + INVENTORY + NETWORK SIGNALS
                    │
                    ▼
             ENTITY DISCOVERY
                    │
                    ▼
              IDENTITY MATCH
                    │
              ┌─────┴─────┐
              ▼           ▼
           KNOWN        UNKNOWN
              │           │
              └─────┬─────┘
                    ▼
             EVIDENCE-BACKED
             DISCOVERY STATE
                    │
                    ▼
                   GRID
```

## Design principles

1. Discovery results retain evidence.
2. Unknown does not mean malicious.
3. Inventory conflicts remain visible.
4. Ownership gaps are first-class findings.
5. Discovery should improve topology without silently rewriting it.