# The Problem

Continuing to manage **employment transitions** in the UAE today requires residents to juggle multiple, loosely‑connected government services:

- Employer processes
- Work‑permit issuance (MOHRE)
- Residency updates (GDRFA‑Dubai)
- Medical fitness certificates
- Identification services

Each service has its own portal, timeline, and status tracking. Residents often:

- Manually check each system for updates
- Experience long, unpredictable waiting periods between dependent steps
- Lack visibility on what action is required next

Continuum does **not** simply expose another portal; it **orchestrates** the entire journey, coordinating dependencies so the resident only deals with a single AI‑driven interaction.

---

## Today’s Fragmented Workflow

```mermaid
gantt
    title Employment Change – Current Process
    dateFormat  YYYY-MM-DD
    section Reporting
        Report Change            :a1, 2023-01-01, 1d
    section Work Permit
        Work‑Permit Processing   :a2, after a1, 5d
    section Residency
        Residency Update         :a3, after a2, 3d
    section Medical/ID
        Medical Fitness          :a4, after a3, 2d
        ID Issuance             :a5, after a4, 2d
    section Completion
        Final Status Check       :a6, after a5, 1d
```

*Multiple handoffs, manual status checks, and uncertain waiting times.*

---

### Why Coordination Matters

The core challenge is **dependency management** – a later service cannot start until a prior one finishes. Continuum tracks these dependencies, proactively notifies the resident, and only escalates to a human officer when a government decision is required.
