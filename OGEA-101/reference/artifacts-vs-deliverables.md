# Artifacts vs Deliverables (and Building Blocks) — OGEA-101

**Exam weight:** High for **definition / distinction** questions. Part of the TOGAF **Architecture Content Framework** triad: **Deliverables · Artifacts · Building Blocks**.

---

## One-line distinction

| Term | One-line meaning |
|------|------------------|
| **Deliverable** | A **formal** work product — typically **contractually specified**, reviewed/signed off, and archived (e.g. Architecture Definition Document, Architecture Roadmap). |
| **Artifact** | A more **granular** architecture work product that **describes** the architecture from a specific perspective (often a **catalog**, **matrix**, or **diagram**). Usually **lives inside** deliverables. |
| **Building Block** | A **reusable** component of business, IT, or architectural capability (**ABB** logical / **SBB** solution). |

**Memory:** Deliverable = **signed package**. Artifact = **piece of description** inside it. Building Block = **reusable chunk of capability**.

---

## Deliverables (exam hooks)

- Formal outputs of an architecture project/cycle.  
- Examples: **Architecture Vision**, **Architecture Definition Document (ADD)**, **Architecture Requirements Specification (ARS)**, **Architecture Roadmap**, **Architecture Contract**, **Statement of Architecture Work**, **Implementation and Migration Plan**.  
- Stakeholders often **review and approve** deliverables.  
- Lifecycle by phase: [deliverable-lifecycle-by-phase.md](deliverable-lifecycle-by-phase.md).

---

## Artifacts (exam hooks)

- Atomic (or near-atomic) **architecture descriptions**.  
- TOGAF commonly groups artifacts as:
  - **Catalogs** — lists of things (e.g. application catalog, actor catalog)
  - **Matrices** — relationships between things (e.g. application/organization matrix)
  - **Diagrams** — visual representations (e.g. business process diagram, network diagram)
- Artifacts address **stakeholder concerns** via **views** (constructed per **viewpoints**).  
- Many artifacts are **contained in** the ADD and other deliverables.

**Trap:** An “application catalog” is an **artifact**, not a deliverable by itself. The **ADD** that includes that catalog is a **deliverable**.

---

## Building Blocks (compact)

| | |
|--|--|
| **ABB** | Architecture Building Block — **logical** reusable architecture component |
| **SBB** | Solution Building Block — **implements** an ABB (product/system/component) |

Detail: [../02-definitions-drill.md](../02-definitions-drill.md).

Building blocks can be **described by** artifacts and **documented within** deliverables; they are not the same thing as either.

---

## How they fit together

```text
Deliverable (e.g. ADD)
  └── contains Artifacts (catalogs, matrices, diagrams / views)
        └── describe Building Blocks (ABBs → later SBBs)
```

---

## Quick elimination drill

1. Formally reviewed and signed-off Architecture Roadmap → **Deliverable**  
2. Application/data matrix inside the ADD → **Artifact**  
3. Logical “Customer Management” capability package → **ABB** (building block)  
4. Vendor CRM product implementing that capability → **SBB**  
5. Architecture Definition Document → **Deliverable** (contains many artifacts)  
6. Network connectivity diagram → **Artifact**

---

## Related traps

| Don’t confuse… | With… |
|----------------|--------|
| Deliverable | Artifact (formal package vs granular description) |
| Artifact | View (a view is a kind of representation for concerns; artifacts often realize views) |
| Building Block | Deliverable (capability chunk vs signed document) |
| Architecture Repository area | Deliverable (storage classification vs project work product) |
