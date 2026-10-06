# Miscellaneous — cross-cutting OGEA-101 topics

Topics that often appear on the exam but are **not** tied to a **single** ADM phase. Use this with [02-definitions-drill.md](02-definitions-drill.md), [03-governance-EFG-drill.md](03-governance-EFG-drill.md), and [`phases/`](phases/). **Confirm** wording against the official **TOGAF Standard, 10th Edition** and your accredited materials.

---

## 1. Architecture Repository (whole-ADM)

**What it is:** The **logical** place where the enterprise classifies and stores **architecture knowledge** (not necessarily one physical database).

**Relevance to phases:** **Not owned by one phase.** **Preliminary** often defines **how** it is used (part of EA **capability**). **Phases A–H** **produce and update** artifacts that map into repository **areas** over time. **Governance** records especially connect to **governance** activities (e.g. board decisions, Phase **G** compliance).

### Seven areas — keyword → area (exam pattern)

| Area | One-line role | Stem keywords |
|------|----------------|---------------|
| **Architecture Metamodel** | Rules for **how** your org structures architecture descriptions | metamodel, entities/relationships in descriptions |
| **Architecture Capability** | **Who** does EA: roles, skills, operating model | capability, skills, roles, EA team |
| **Architecture Landscape** | **States** of architecture (strategic → operational), baseline/target breadth | landscape, strategic/segment/capability/operational |
| **Standards Information Base** | **Standards** catalog (mandatory + voluntary) | standards, compliance to standards catalog |
| **Reference Library** | **Reference models**, **patterns**, **templates**, guidelines | patterns, templates, reference model |
| **Governance Log** | **Decisions**, **compliance** outcomes, waivers | governance decision, compliance result, exception record |
| **Architecture Requirements Repository** | **Architecture requirements** collected across ADM | requirements repository, architecture requirements |

---

## 2. Enterprise Continuum

**What it is:** A way to classify assets from **generic** → **organization-specific**.

- **Architecture Continuum:** Foundation → Common Systems → Industry → **Organization-Specific** architectures.  
- **Solutions Continuum:** Parallel idea for **solutions** (generic products → org-specific implementations).

**Exam pattern:** “Most specific to our organization” → **Organization-Specific** end. **Standards** often sit with **standards** / generic side conceptually; **org-specific** is the tailored end.

---

## 3. Architecture Content Metamodel (recognition only)

**What it is:** A structured way to define **types of architecture content** and **relationships** between them so descriptions are **consistent** and **complete enough** for purpose.

**Exam level:** **What problem does it solve?** — organizing content. **Not** deep customization for Level 1.

---

## 4. Architecture partitions

**What it is:** Splitting the **overall** architecture into **smaller** architectures (e.g. by scope, time, team, risk) so they can be developed and governed **manageably**.

**Exam level:** **Why partition?** — complexity, separation of concerns, parallel work, clarity of ownership.

---

## 5. Business scenarios

**What they are:** A method to **describe a business problem**, identify **stakeholders** and **concerns**, and **scope** the architecture work.

**Exam pattern:** “Why use a business scenario?” → **scope**, **stakeholders**, **concerns**, **problem clarity** — not “replace Phase D.”

---

## 6. Gap analysis

**What it is:** Compare **baseline** vs **target** to identify **gaps** (missing or changed capabilities, data, applications, technology).

**Exam pattern:** Appears **across** domain phases where baseline/target is defined — not one exclusive phase label; questions often test **definition** and **purpose**.

---

## 7. Iteration and tailoring

- **Iteration:** The ADM is applied **iteratively**; work in **later** phases can **refine** earlier results. **Requirements Management** is **continuous**.  
- **Tailoring:** The ADM is **adapted** to the enterprise (context, scale, risk) — often established in **Preliminary**, not ignored.

---

## 8. Principles and governance (compact pointers)

- **Principles:** Guide **trade-offs**; constrain decisions; must be **usable** (see [03-governance-EFG-drill.md](03-governance-EFG-drill.md)).  
- **Architecture Board:** **Governance** and **decisions** (compliance, direction, exceptions).  
- **Architecture contracts** and **compliance assessments:** Strongly associated with **Phase G** (see [03-governance-EFG-drill.md](03-governance-EFG-drill.md)).

---

## 9. Building blocks (compact pointer)

- **ABB** vs **SBB:** [02-definitions-drill.md](02-definitions-drill.md).

---

## 10. Lower-yield (skim unless mocks fail here)

- Deep **reference model** internals (e.g. TRM/III-RM detail).  
- **TOGAF Library** / document taxonomy — occasional recognition.  
- Memorizing **long step lists** inside phases — Foundation usually tests **goals**, **position**, **outputs**, not every sub-step.

---

## 11. Cross-cutting exam traps

| Trap | Rule of thumb |
|------|----------------|
| Preliminary vs A | Preliminary = **EA capability** for the org; A = **this cycle’s** vision and proceed. |
| B vs C vs D | **Business** vs **Data/App** vs **Technology**. |
| E vs F vs G | **Work packages** vs **roadmap/timing** vs **build conformance**. |
| Viewpoint vs view | Viewpoint = **conventions**; view = **result**. |
| “Primary / best” | Pick **TOGAF definition**, not casual IT habit. |
