# OGEA-101 — Phase E vs F vs G + governance (Todo: governance-eFG)

## E vs F vs G (one line each)

- **E — Opportunities & Solutions:** **What** major chunks of change — consolidating gaps into **work packages** and delivery approaches.  
- **F — Migration Planning:** **When** and **how** to transition — **roadmap**, sequencing, timing.  
- **G — Implementation Governance:** **Police during build** — ensure projects **conform**; **architecture contracts**; **compliance assessments**.

If the stem mentions **roadmap / transition / timing / migration plan** → **F**.  
If **work packages / grouping initiatives / consolidating gaps** → **E**.  
If **contracts / compliance / conformance during implementation** → **G**.

**Examples:** E = group gaps into “KYC platform” + “decision engine” work packages; F = put them on an 8-quarter roadmap; G = vendor must pass compliance vs ADD/ARS. Gallery: [reference/exam-examples-gallery.md](reference/exam-examples-gallery.md).

---

## Compliance assessments (exam vocabulary)

Used to **measure** how implementation (or partner systems) **conforms** to the architecture. Tied to **Phase G** context (implementation governance), not to initial visioning.

**Example:** Payments project reviewed for mandatory identity integration → non-conformant → remediation (not an EA maturity score).

**Do not confuse with Architecture Maturity Model:** compliance = **implementation** conformance; maturity = how developed the **EA practice** is (see [reference/landscape-deliverables-maturity.md](reference/landscape-deliverables-maturity.md)).

More techniques (gap analysis, readiness, RM impact, E/F matrices): [reference/techniques-cheat-sheet.md](reference/techniques-cheat-sheet.md).

---

## Architecture contracts (exam vocabulary)

Agreement between **governing authority** (e.g., Architecture Board / EA governance) and **development organization** defining deliverables, **compliance**, metrics, acceptance criteria — supports **Phase G**.

**Example:** Vendor Y commits to API gateway + audit logging and accepts compliance reviews before go-live.

---

## Architecture Board (recognition level)

**Decision body** for architecture governance: reviews compliance, resolves impacts, approves exceptions, owns principles enforcement (wording varies; exam favors **governance + decision-making** role).

**Often-tested responsibility:** **enforcement of architecture compliance**.  
**Trap:** Don’t pick “assess maturity of the architecture discipline” when the stem asks about Board **compliance** responsibility.

**Example:** Board approves an 18-month exception to keep a legacy payments hub.

**Governance hierarchy:** Architecture Governance typically operates **within a hierarchy** (e.g. with Corporate / Technology / IT governance) — not in isolation. See [reference/togaf10-official-paper-gaps.md](reference/togaf10-official-paper-gaps.md).

---

## Architecture principles (exam angle)

- **Purpose:** Guide consistent decision-making; translate strategy into architectural **constraints**.  
- **Good principles** are understandable, stable enough, and usable — exams may ask **what principles do** (govern trade-offs) vs memorizing sample text.
- **TOGAF template (exact four parts):** **Name**, **Statement**, **Rationale**, **Implications**.  
  - **Name** — memorable essence of the rule; avoid tech-platform lock-in.  
  - **Statement** — unambiguous fundamental rule.  
  - **Rationale** — **business** benefits / why it matters.  
  - **Implications** — business/IT requirements, costs, activities; impact if not followed.  
- **Mini example (“Buy over Build”):** Name → Statement (prefer buy) → Rationale (speed/cost) → Implications (RFP, SaaS review, Board exceptions). Full N-S-R-I example: [reference/exam-examples-gallery.md](reference/exam-examples-gallery.md) · [reference/architecture-principles-and-adr.md](reference/architecture-principles-and-adr.md).

---

## Elimination drill (choose E, F, or G only)

1. Finalize a time-phased plan to move from baseline to target across portfolios. → **F**  
2. Identify major work packages after completing gap analysis across B/C/D. → **E**  
3. Ensure the supplier’s delivery matches the agreed architecture for the project. → **G**  
4. Define architecture compliance reviews for a major program. → **G**  
5. Group projects into coherent tranches of change. → **E**  
6. Produce a migration roadmap with milestones. → **F**  
7. Sign off an agreement that the project will implement specific building blocks. → **G**  
8. Consolidate cross-domain gaps into candidate solutions. → **E**

---

## Principles + governance quick checks

1. Who typically **approves** architecture exceptions in governance models? → **Architecture Board** (or equivalent governance authority)  
2. Principles primarily exist to? → **Guide and constrain** architecture decisions consistently  
3. Compliance assessments measure? → **Conformance** to architecture  
4. Architecture contracts are most associated with? → **Phase G**  
5. Four components of a TOGAF Architecture Principle? → **Name, Statement, Rationale, Implications**  
6. Which principle component explains **business benefits**? → **Rationale**  
7. Which principle component covers **resources, costs, and activities** to apply the rule? → **Implications**
