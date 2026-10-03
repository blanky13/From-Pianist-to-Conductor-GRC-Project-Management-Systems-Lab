# Orchestra to GRC Systems Map

## System View

The laboratory treats GRC as a coordinated system rather than a collection of isolated documents.

```mermaid
flowchart LR
    A[Business Objective] --> B[Requirements]
    B --> C[Policies and Controls]
    C --> D[Control Owners]
    D --> E[Implementation]
    E --> F[Evidence]
    F --> G[Testing / Audit]
    G --> H[Findings]
    H --> I[Corrective Action]
    I --> E
```

The conductor sits across this flow as the coordination layer.

```mermaid
flowchart TB
    S[Business Objective / Sponsor]
    C[Conductor: GRC / PM Coordination]
    I[IT]
    H[HR]
    O[Operations]
    L[Legal / Privacy]
    A[Audit]

    S --> C
    C --> I
    C --> H
    C --> O
    C --> L
    C --> A
```

## System Failure Patterns

| Musical problem | Systems interpretation |
|---|---|
| Wrong tempo | Schedule/dependency mismatch |
| Missing musician | Unclear ownership or unavailable SME |
| Wrong instrument | Control design does not address the actual objective |
| Too loud | Control creates disproportionate business friction |
| Wrong notes | Process/evidence does not match the documented requirement |
| Poor transition | Weak handoff between teams |
| Section out of sync | Cross-functional dependency failure |
| Recovery after mistake | Incident/risk response and corrective action |

## Key Lesson

A control can exist on paper while the overall system still performs poorly.

This distinction will later connect to:

- control design effectiveness
- operating effectiveness
- evidence quality
- ownership
- dependencies
- risk treatment
- corrective action
