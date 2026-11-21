# TOGAF 10 official-paper gaps (OGEA-101)

Themes that **Open Group–style** Part 1 papers (e.g. B220) hit hard, and that classic “ADM phase one-liner” packs often miss.  
Use after a practice-test miss list. **Paraphrased for study** — confirm against the TOGAF Standard, 10th Edition / your accredited materials.

**Related:** [techniques-cheat-sheet.md](techniques-cheat-sheet.md) (Initial/Residual risk) · [architecture-principles-and-adr.md](architecture-principles-and-adr.md) · phase files

---

## 1. Documentation set — where guidance lives

| Source | Exam meaning |
|--------|----------------|
| **TOGAF Fundamental Content** | Core method/content of the standard |
| **TOGAF Series Guides** | **Practical guidance on how to apply** the TOGAF Standard |
| **TOGAF Library** | Broader body of TOGAF-related material |
| **ADM Techniques** (as a topic) | Techniques that support the ADM — not the same as “Series Guides” |

**Trap:** “How do I apply TOGAF in practice?” → **Series Guides**, not Fundamental Content alone.

---

## 2. What the ADM diagram is (and isn’t)

| Correct | Incorrect |
|---------|-----------|
| A **stylized** graphic showing essential **information flows** | A linear **waterfall** process model |
| | A strict **activity sequence** you must always run left-to-right |

**Exam line:** The ADM graphic is **not** primarily a process-sequence model.

---

## 3. Phase “Output & Outcome” / Essential Knowledge (drill hard)

Official papers often show a table: **Output & Outcome** + **Essential Knowledge** → “Which phase?”

### Phase F (Migration Planning) — memorize

| Output & Outcome (flavor) | Essential Knowledge (flavor) |
|---------------------------|------------------------------|
| An **approved set of projects** with objectives, constraints, **resources**, **start/finish dates** | Resources available to change; how **stakeholder priority/preference** shifts with **value, effort, and risk** |

**Keyword cluster:** approved projects · dates · resources · stakeholder preference vs value/effort/risk → **F**

### Phase H (Architecture Change Management) — memorize

| Output & Outcome (flavor) | Essential Knowledge (flavor) |
|---------------------------|------------------------------|
| Direction to proceed / start developing a Target that addresses **shortfalls** vs stakeholder preferences | Gaps between **approved target** (or preference) and **realization** (**Value Realization**); changes in preference/priority |

**Keyword cluster:** value realization · shortfalls vs preference · new direction for Target → **H** (not G)

### Phase E / G — objective matching (common multi-match)

| Objective flavor | Phase |
|------------------|-------|
| Incremental approach? Identify **Transition Architectures** that deliver continuous business value | **E** |
| Define overall **SBBs** to finalize Target based on **ABBs** | **E** |
| Coordinate Implementation & Migration Plan with enterprise **change portfolio** | **F** |
| Business value and cost of work packages / Transition Architectures understood by stakeholders | **F** |
| Finalize Architecture Roadmap + Implementation and Migration Plan | **F** |
| Ensure **conformance** with Target by implementation projects | **G** |
| Architecture Governance for the solution + implementation-driven **Change Requests** | **G** |
| Ensure the **Enterprise Architecture Capability** meets current requirements | **H** (capability of the EA practice — not project conformance) |

**Trap:** “EA Capability meets current requirements” feels like Preliminary — in objective-match questions it is often tagged to **H**.

---

## 4. Principle quality criteria (beyond N-S-R-I)

N-S-R-I = how you **write** a principle. Papers also ask **recommended criteria** for a good set of principles:

| Criterion | Exam hook |
|-----------|-----------|
| **Understandable** | Clear to decision-makers |
| **Robust** | Enable good decisions in varied situations |
| **Complete** | Cover needed situations |
| **Consistent** | Principles don’t conflict destructively |
| **Stable** | **Enduring** and yet able to **accommodate change** |

**Classic stem:** “enduring and yet able to accommodate change” → **Stability**

---

## 5. Architecture Repository — minimize information

A well-run repository **minimizes** information gathered and maintained.  
Do **not** try to capture every artifact listed in the standard “just because.”  
Capture what the **current architecture project** needs (plus minimal traceability).

**Trap:** “Complete repository of all TOGAF artifacts is required” → **False**

---

## 6. Scope dimensions — Depth vs Breadth

When scoping an architecture, dimensions typically include (among others):

| Dimension | Meaning |
|-----------|---------|
| **Breadth** | How much of the enterprise is covered |
| **Depth** | To what **level of detail** the architecting effort goes; how much architecture is “enough” vs design/engineering |

**Classic stem:** “appropriate level of detail based on intended use” → **Depth**

(Also distinguish landscape levels Strategic/Segment/Capability — those are about **breadth/partitioning of the landscape**, not the Depth dimension wording.)

---

## 7. Approved vs finalized documents

In the ADM:

- Documents reviewed and approved are designated **“approved”** per governance practice.  
- **Approved does not necessarily mean finalized.**  
- They may **evolve** in later phases, but only via **change control / governance**.

**Trap:** “Approved = frozen forever” → **False**

---

## 8. Governance — hierarchy, Board, directs & controls

### Hierarchy
Architecture Governance typically does **not** operate in isolation. It sits in a **hierarchy**, which can include:

- Corporate Governance  
- Technology Governance  
- IT Governance  
- Architecture Governance  

### Architecture Board
A core responsibility: **enforcement of architecture compliance**.  
**Trap:** Don’t pick “conduct maturity assessment of the discipline” when the stem asks Board responsibility for **compliance enforcement**.

### “Directs and controls”
Central to governance: **directs and controls**.  
Typical exam framing: the **stakeholder** directs; the **architecture practitioner** and **implementer** are directed and controlled (practitioner does not “govern the stakeholder”).

---

## 9. Architecture Capability (vs “an architecture”)

**Architecture Capability** = organization structures, roles, responsibilities, skills, and processes that enable effective architectural activity.  
Diagrams of that capability are **not** the same as “an Enterprise Architecture” (the models of the business/IT) or “the metamodel.”

**Preliminary** establishes/improves it; **Phase H** may ensure it still meets current requirements.

---

## 10. Deliverable definition matching (Vision example)

Be ready to **match definitions**, not only names:

| Deliverable | Definition flavor |
|-------------|-------------------|
| **Architecture Vision** | Summary of changes to the enterprise that will accrue from successful deployment of the **Target Architecture** |
| **Architecture Contract** | Joint agreement between development partners and sponsors on deliverables, quality, fitness-for-purpose |
| **Request for Architecture Work** | From sponsoring organization to architecture organization to **trigger** a cycle |
| **Architecture Definition Document** | Container for core architectural artifacts and related information |

---

## 11. Why use Enterprise Architecture (benefits)

A good EA facilitates effective **governance**, **management**, **risk management**, and **exploitation of opportunities** — including supporting major change such as digital channels (it is **not** “unsuitable because Agile”).

---

## 12. Initial vs Residual risk (pointer)

| Level | Meaning |
|-------|---------|
| **Initial** | Before mitigating actions |
| **Residual** | After mitigating actions |

Detail: [techniques-cheat-sheet.md](techniques-cheat-sheet.md).

---

## Rapid self-check (close book)

1. Practical how-to apply TOGAF → **Series Guides**  
2. ADM graphic → **information flows**, not waterfall  
3. Approved projects + dates + resources → **Phase F**  
4. Value realization / shortfalls vs preference → **Phase H**  
5. Enduring + accommodates change → principle **Stability**  
6. Repository should → **minimize** stored info  
7. Level of detail when scoping → **Depth**  
8. Approved documents → **not always finalized**  
9. Governance operates → in a **hierarchy**  
10. Board responsibility often tested → **enforce compliance**  
11. Risk before mitigation → **Initial**  
12. Stakeholder **directs**; practitioner/implementer **controlled** → governance “directs and controls”

---

## How to use after B220

1. Re-read this file once.  
2. Re-answer only your wrong B220 items.  
3. Full timed B220 again — target **≥28/40**.  
4. Log remaining misses in [../05-miss-tag-log.md](../05-miss-tag-log.md).
