# Requirements Management (central to the ADM)

**Purpose:** **Continuously** identify, store, and manage **architecture-related requirements** throughout every ADM phase.

## Key terms

| Term | Short description |
|------|-------------------|
| **Architecture requirement** | A requirement that **constrains** or **defines** the architecture (not only software backlog items). |
| **Requirements baseline** | Agreed set of requirements that architecture work must **satisfy** at a point in time. |
| **Central hub** | Requirements Management connects to **each** phase — not a one-off step at the start. |

## Architecture requirement — examples (vs backlog)

| Architecture requirement (exam flavor) | Not the same as (backlog / UI feature) |
|----------------------------------------|----------------------------------------|
| Customer data must remain in Region X (residency) | “As a user I can edit my profile photo” |
| All domain apps must use the enterprise identity service | “Add a forgot-password link” |
| Mortgage decisioning availability target: 99.9% | “Fix CSS spacing on the login page” |
| Integrations must go through the approved API gateway | “Build a one-off point-to-point script for this release” |
| Audit logging required for all credit decisions | “Show a green checkmark when submit succeeds” |
| Interoperability: exchange customer master data via the canonical model | “Hard-code customer fields in one screen only” |

**Exam hook:** Architecture requirements are often **constraints, qualities, standards, interoperability, compliance, SLAs** — they shape the **architecture**. Product backlog items are often **feature behaviors** for a single solution increment.

## Functions (exam level)

- Keep requirements **aligned** as architecture moves from vision through implementation and change.
- Support **traceability** from business need to architectural decisions (at a conceptual exam level).

## Links to other phases

- **All phases (Preliminary through H):** The process **interacts** with every phase; exams often test that it is **ongoing**, not confined to Phase A only.

## Key deliverables (create / update)

| Deliverable | Role of Requirements Management |
|-------------|----------------------------------|
| **Architecture Requirements Specification** | Continuously **fed and updated**; drafts grow in **B–D**, finalize in **F** |
| **Requirements Impact Assessment** | Produced when changes affect requirements |
| **All phase outputs** | Requirements **interact with every phase** |

## Boundaries

- **Not a domain phase:** It does **not** replace **B/C/D** — it does not “own” business/data/app/tech models.
- **Not the same as Phase H:** **Requirements Management** is about the **requirements** stream; **Phase H** is broader **architecture change management** (monitoring change, updating the architecture, cycles).

Lifecycle table: [../reference/deliverable-lifecycle-by-phase.md](../reference/deliverable-lifecycle-by-phase.md).
