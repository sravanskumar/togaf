# Architecture deliverables — create / update by ADM phase (OGEA-101)

**Exam use:** Match the **deliverable** to **where it is mainly created** vs **refined/finalized**. Iteration means artifacts can be revisited; the table shows the **typical exam story**.

**Companion distinctions:** [landscape-deliverables-maturity.md](landscape-deliverables-maturity.md) (what each deliverable *is*).

**Qualitative vs quantitative (classic trap)**

- **Architecture Definition Document (ADD)** → **qualitative** view (architect’s intent; baseline/target/views).  
- **Architecture Requirements Specification (ARS)** → **quantitative** view (measurable criteria an implementation must meet).  
- They are **companions**, not substitutes.

---

## Master lifecycle table

| Deliverable | Mainly **created / drafted** | **Updated / refined** | **Finalized / used heavily** |
|-------------|------------------------------|------------------------|------------------------------|
| **Architecture Principles** | **Preliminary** | Confirmed/elaborated in **A**; change via governance / **H** | Used in **all** phases |
| **Request for Architecture Work** | Sponsor; may come from **Preliminary**, **F**, or **H** | — | Triggers **Phase A** |
| **Statement of Architecture Work** | **Phase A** (approved) | Refined **B–F** as scope evolves; update in **H** if needed | Guides the cycle |
| **Architecture Vision** | **Phase A** | May refine later if iteration requires | Constrains **B–D** |
| **Communications Plan** | **Phase A** | As needed | Used through delivery |
| **Capability Assessment** | **Phase A** (also inputs in **E**) | As needed | Informs feasibility |
| **Architecture Definition Document (ADD)** | Drafted / built across **B, C, D** (domain architectures) | Updated in **E**; Transition Architectures reflected | **Finalized in F**; used in **G** for conformance |
| **Architecture Requirements Specification (ARS)** | Drafted across **B, C, D** (+ Requirements Management) | Updated in **E**; continuous via **Requirements Management** | **Finalized in F**; feeds contracts / **G** |
| **Architecture Roadmap** | **Roadmap components** identifiable in **B, C, D**; **initial complete roadmap in E** | Incrementally developed **E and F** | **Finalized in F** |
| **Transition Architectures** | Identified in **E** | Refined in **F** | Support migration |
| **Implementation and Migration Plan** | Version **0.1 in E** | Completed in **F** | **Finalized in F** |
| **Implementation Governance Model** | **Phase F** | — | Used in **G** |
| **Architecture Contract** | **Prepared in F** | Signed/used in **G**; may update with change | **G** governance |
| **Compliance Assessment** | **Phase G** | May inform **H** | Measures implementation conformance |
| **Change Request** | **G** / **H** (also related to F/H pathways) | — | May trigger new cycle / **Request for Architecture Work** |
| **Requirements Impact Assessment** | **Requirements Management** (ongoing) | Every phase as requirements change | Protects integrity of ARS |

---

## Focus: the three you asked about

### Architecture Definition Document (ADD)

| | |
|--|--|
| **What** | Container for core architecture artifacts: baseline, target, (transition), views, supporting analysis across business/data/application/technology. |
| **Creates / drafts** | **Phases B, C, D** (domain-by-domain growth of baseline/target content). High-level direction starts in **A** (Vision), but the **ADD** itself is the B–D artifact container. |
| **Updates** | **Phase E** (consolidate opportunities/solutions, transition states). |
| **Finalizes** | **Phase F**. |
| **Uses later** | **Phase G** (what implementation must conform to). |

### Architecture Requirements Specification (ARS)

| | |
|--|--|
| **What** | Quantitative requirements/constraints/measurable criteria for compliance with the architecture. |
| **Creates / drafts** | **Phases B, C, D**, with continuous input from **Requirements Management**. |
| **Updates** | **Phase E**; continuously via **Requirements Management** (and Requirements Impact Assessment). |
| **Finalizes** | **Phase F**. |
| **Uses later** | Often a major input to **Architecture Contract** / implementation in **G**. |

### Architecture Roadmap

| | |
|--|--|
| **What** | Work packages on a **timeline** from Baseline → Target; business value by stage; Transition Architectures as intermediate steps. |
| **Creates** | **Components** may appear from **B, C, D**; **first complete Architecture Roadmap in Phase E** (e.g. v0.1). |
| **Updates** | Incrementally through **E and F**. |
| **Finalizes** | **Phase F** (with Implementation and Migration Plan). |

**Exam mnemonic for ADD / ARS / Roadmap:**  
**B–D draft** → **E update / first full roadmap** → **F finalize**.

---

## Other high-yield create/update pairs

| If the stem says… | Think… |
|-------------------|--------|
| Principles for the EA practice | **Preliminary** create; used everywhere |
| Approve Statement of Architecture Work / Vision | **Phase A** |
| Draft ADD with Business / Data / App / Tech detail | **B / C / D** |
| First complete roadmap + work packages / Transition Architectures | **Phase E** |
| Finalize roadmap + Implementation and Migration Plan | **Phase F** |
| Sign Architecture Contract / compliance assessments | **Phase G** |
| Change requests; possible new Request for Architecture Work | **Phase H** (and related G/H) |
| Requirements continuously identified and managed | **Requirements Management** (all phases) |

---

## Mini drill

1. Where is the Architecture Roadmap **finalized**? → **F**  
2. Where does the **first complete** Architecture Roadmap typically appear? → **E**  
3. Where is the ADD mainly **built** domain-by-domain? → **B, C, D**  
4. ADD vs ARS: qualitative intent vs quantitative criteria? → **ADD qualitative · ARS quantitative**  
5. Architecture Contract mainly **signed/used** in? → **G** (often prepared in **F**)  
6. Architecture Principles mainly **established** in? → **Preliminary**
