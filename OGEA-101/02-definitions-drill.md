# OGEA-101 — Definitions & repository drill (Todo: definitions-core)

## ABB vs SBB

| Term | Exam-oriented definition |
|------|---------------------------|
| **Architecture Building Block (ABB)** | A **logical** reusable component of **enterprise** architecture — captures **capability** and **behavior** at the architecture level. |
| **Solution Building Block (SBB)** | A **real** component that **implements** an ABB — product, system, vendor artifact. |

**Elimination trick:** If the stem says “logical / architecture description / capability package” → lean **ABB**. If “implemented by vendor product / deployed component” → **SBB**.

---

## Stakeholder / concern / viewpoint / view

| Term | Exam-oriented definition |
|------|---------------------------|
| **Stakeholder** | Individual, team, or org with interests in (or concerns about) the architecture/outcomes. |
| **Concern** | Key interest of a stakeholder that architecture should address (security, cost, agility, …). |
| **Viewpoint** | **Specification** of the conventions for a class of views — the **recipe** (metamodel, language, concerns addressed). |
| **View** | **Result** of applying a viewpoint — the **actual** architecture representation for stakeholders. |

**Memory:** Viewpoint = **recipe**; View = **dish**; Concern = **what matters** to the stakeholder.

---

## Enterprise Continuum (direction)

Generic / industry-standard material on the **left** → more **organization-specific** on the **right**.

- **Architecture Continuum:** Foundation → Common Systems → Industry → **Organization-Specific** architectures.  
- **Solutions Continuum:** Foundation Solutions → Common Systems Solutions → Industry Solutions → **Organization-Specific** solutions.

**Exam pattern:** “Most tailored to the organization” = **Organization-Specific** end.

---

## Architecture Repository — seven areas (labels)

Memorize **names** and **what kind of thing** lives there:

1. **Architecture Metamodel** — metamodel for org’s architecture descriptions.  
2. **Architecture Capability** — definition of teams, roles, skills needed to run EA.  
3. **Architecture Landscape** — current and target states at **strategic**, **segment**, **capability**, **operational** levels (breadth of architecture state).  
4. **Standards Information Base** — standards (voluntary + mandatory) the org must comply with.  
5. **Reference Library** — guidelines, templates, patterns, **reference models**.  
6. **Governance Log** — governance record (decisions, compliance, exceptions).  
7. **Architecture Requirements Repository** — collected requirements output from ADM.

**Drill:** Cover the right column; recall the **seven names** in any order, then match to “what lives there.”

---

## 10 rapid flash questions

1. An installed CRM product instance mapping to a logical “Customer Management” capability is best described as? **SBB**  
2. The conventions that define how to draw a security architecture for auditors define a? **Viewpoint**  
3. The actual diagram delivered to auditors is a? **View**  
4. The catalog of **mandatory organizational standards** maps most directly to which Architecture Repository area? **Standards Information Base**  
5. Reference models and templates in the repo → **Reference Library**  
6. Decisions and compliance outcomes log → **Governance Log**  
7. Most organization-specific architecture description sits toward which end of the Architecture Continuum? **Organization-Specific**  
8. Phase C develops architectures for which domain pair? **Data and Application** (Information Systems)  
9. ABB describes **logical** architecture building blocks: Y/N? **Y**  
10. Viewpoint is the **resulting diagram**: Y/N? **N** (that’s the view)
