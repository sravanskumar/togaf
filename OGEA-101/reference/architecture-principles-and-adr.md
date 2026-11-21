# Architecture Principles (TOGAF) and Architecture Decision Records (ADR)

**Exam note:** The **four-part Architecture Principle** template is **TOGAF Foundation–relevant**. **ADRs** are a common **industry practice** for recording decisions; they are **not** a required OGEA-101 syllabus topic, but they link cleanly to **principles**, **governance**, and **traceability**.

---

## Architecture Principle template (TOGAF — MUST memorize)

A well-defined Architecture Principle follows this **exact** four-component structure:

| Component | What it does | Exam hooks |
|-----------|--------------|------------|
| **Name** | Short label for the rule; easy to remember; captures the essence. Avoid specific tech platforms so it stays enduring. | e.g. “Data is an Asset”, “Buy over Build” |
| **Statement** | Succinct, unambiguous statement of the **fundamental rule**. Information-management principle statements are often similar across organizations. | The rule itself |
| **Rationale** | **Business benefits** of following the principle, in **business** language; links architecture/IT principles to how the business already operates. | Why we care |
| **Implications** | **Requirements** on business and IT to carry out the principle (resources, costs, activities/tasks); often includes impact if the principle is **not** followed. | What must change / what it costs |

**Mnemonic:** **N-S-R-I** — Name, Statement, Rationale, Implications.

**Worked example (“Buy over Build”)** — see [exam-examples-gallery.md](exam-examples-gallery.md) §7 for Name / Statement / Rationale / Implications filled in.

### Recommended criteria for a good set of principles

| Criterion | Hook |
|-----------|------|
| **Understandable** | Clear to decision-makers |
| **Robust** | Supports good decisions in varied situations |
| **Complete** | Covers needed situations |
| **Consistent** | Principles don’t conflict destructively |
| **Stable** | **Enduring** and yet able to **accommodate change** |

**Exam trap:** “enduring and yet able to accommodate change” → **Stability** (not Robustness/Completeness).

**Where this lives in ADM:** Architecture principles are typically established in the **Preliminary** Phase and then used to constrain decisions across the ADM (and in governance).

More official-paper gaps: [togaf10-official-paper-gaps.md](togaf10-official-paper-gaps.md).

---

## Architecture Decision Record (ADR) — practice template

Use ADRs to **document a specific architectural choice** and show how it aligns with (or trades off against) TOGAF principles and constraints.

### Core components

| Component | What it does |
|-----------|--------------|
| **Title** | Short, often **numbered** noun phrase summarizing the decision (e.g. `ADR-004: Use PostgreSQL for Primary Data Storage`). |
| **Status** | Lifecycle state: Proposed, Accepted, Rejected, Deprecated, or Superseded (link the newer ADR if superseded). |
| **Context** | Business drivers, technical constraints, landscape realities (e.g. brownfield), and **relevant TOGAF Architecture Principles** that make the decision necessary now. |
| **Decision** | The explicit choice in **active voice** (e.g. “We will use…”). |
| **Consequences** | Trade-offs: positives, negatives, risks, and follow-up work required because of the choice. |

### Optional (extended / MADR-style)

| Component | What it does |
|-----------|--------------|
| **Considered Options** | Alternatives evaluated alongside the chosen path. |
| **Pros and Cons of the Options** | Why rejected options fell short against context and principles. |
| **Links / Traceability** | References to epics, requirements, or governing **TOGAF principles**. |

### Principles ↔ ADR (how they fit together)

- **Principles** = standing **rules** (Name / Statement / Rationale / Implications).  
- **ADR** = a **dated decision** under those rules (and constraints), with status and consequences.  
- In TOGAF terms, ADRs support **governance transparency**; they do **not** replace Architecture Board decisions, contracts, or compliance assessments.
