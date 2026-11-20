# Artifacts by ADM phase — produce / update / circumstances (OGEA-101)

**Companion files**

- Definitions: [artifacts-vs-deliverables.md](artifacts-vs-deliverables.md)  
- Deliverable packages: [deliverable-lifecycle-by-phase.md](deliverable-lifecycle-by-phase.md)

**Exam depth:** Know **artifact class** (catalog / matrix / diagram), **home phase**, and **when it gets updated**. Do **not** memorize every TOGAF artifact name — scenarios usually say “process diagram”, “application portfolio catalog”, “matrix of apps to org units”, etc.

**Rule of thumb**

- Artifacts are **created** when that domain/concern is being architected.  
- They are **updated** when baseline/target changes, gaps are resolved, transition states appear, requirements change, or iteration revisits earlier work.  
- Most architecture-definition artifacts end up **inside the ADD** (and related deliverables).

---

## Artifact classes (always)

| Class | What it is | Example |
|-------|------------|---------|
| **Catalog** | List of things of the same type | Application portfolio catalog, actor/role catalog |
| **Matrix** | Relationships between two (or more) types | Application/organization matrix, data entity/business function matrix |
| **Diagram** | Visual model of structure or behavior | Business process diagram, application communication diagram, network diagram |

---

## Phase overview — what kinds of artifacts appear

| Phase | Mainly **produces** (typical) | Often **updates** | Circumstances for update |
|-------|-------------------------------|-------------------|--------------------------|
| **Preliminary** | Few architecture-description artifacts; more **capability/governance** setup artifacts (principles catalog-style lists, framework tailoring notes) | When EA capability or principles change | Org redesign of the EA practice |
| **A — Vision** | Stakeholder map; high-level solution concept diagrams; value-chain / capability overviews at **vision** depth; business scenario supporting artifacts | If scope/stakeholders change | New stakeholder concern; SoAW scope change |
| **B — Business** | Business catalogs (actors, roles, capabilities, value streams); business matrices; business diagrams (process, organization, business footprint) | Iteration after C/D discoveries; requirement changes | Gap closure; process redesign; RM impact |
| **C — Information Systems** | **Data** catalogs/matrices/diagrams; **Application** catalogs/matrices/diagrams | After tech constraints (D) or business changes (B) | New entity, app dependency, interoperability need |
| **D — Technology** | Technology catalogs; tech matrices; environments/platform/network diagrams | When solution options change in E or standards change | Platform choice, standards update |
| **E — Opportunities & Solutions** | Solution concept diagrams; consolidated dependency matrices; transition-related views; work-package oriented artifacts | ADD/ARS-related artifacts from B–D as solutions consolidate | Grouping gaps into solutions; Transition Architecture states |
| **F — Migration Planning** | Roadmap visuals; migration/transition diagrams; prioritized work-package views | Final alignment of B–E artifacts to migration sequence | Sequencing, dependencies, funding tranches |
| **G — Implementation Governance** | Compliance-related assessment artifacts/reports; contract conformance evidence | Little “new domain modeling”; may annotate deviations | Compliance findings; waivers; Change Requests |
| **H — Change Management** | Change-impact views; updated landscape snapshots as needed | Any prior artifacts affected by environmental change | Regulation, strategy, tech disruption |
| **Requirements Management** | Requirements catalogs/lists; impact assessment artifacts | Continuously | Any requirement add/change/delete |

---

## Representative artifacts by phase (exam-friendly examples)

### Preliminary
| Artifact flavor | Produced? | Updated when… |
|-----------------|-----------|----------------|
| Principles list / catalog of principles | Yes (as content supporting principles) | Governance changes a principle |
| Tailoring / framework description artifacts | Yes | EA method changes |

### Phase A — Architecture Vision
| Example artifact | Produced | Updated when… |
|------------------|----------|----------------|
| Stakeholder map (matrix/catalog) | Yes | New stakeholders/concerns |
| Value chain / capability overview diagram (high level) | Yes | Vision/scope change |
| Solution concept diagram (outline) | Often | Options change later (esp. E) |

### Phase B — Business Architecture
| Example artifact | Produced | Updated when… |
|------------------|----------|----------------|
| Organization / actor / role catalog | Yes | Org redesign |
| Business capability catalog | Yes | Capability model changes |
| Value stream catalog / diagrams | Yes | Value-creation path changes |
| Business interaction / process diagrams | Yes | Process redesign; gaps closed |
| Business footprint / service diagrams | Yes | Service boundary changes |
| Business ↔ information matrices (early) | Often | Feeds Phase C |

### Phase C — Data Architecture
| Example artifact | Produced | Updated when… |
|------------------|----------|----------------|
| Data entity / data component catalog | Yes | New entities; master data scope |
| Data entity/business function matrix | Yes | Process or entity changes |
| Data dissemination / security / lifecycle diagrams | Yes | Sharing, retention, classification changes |

### Phase C — Application Architecture
| Example artifact | Produced | Updated when… |
|------------------|----------|----------------|
| Application portfolio catalog | Yes | App rationalization |
| Application/organization or application/function matrix | Yes | Ownership or function mapping changes |
| Application communication / use-case diagrams | Yes | Integration design changes |

### Phase D — Technology Architecture
| Example artifact | Produced | Updated when… |
|------------------|----------|----------------|
| Technology standards / portfolio catalog | Yes | Standards Information Base–aligned updates |
| Application/technology matrix | Yes | Platform mapping changes |
| Environments & locations / network / platform diagrams | Yes | Infra or cloud topology changes |

### Phase E — Opportunities & Solutions
| Example artifact | Produced / emphasized | Updated when… |
|------------------|----------------------|----------------|
| Project context / benefits diagrams | Yes | Work-package regrouping |
| Application & technology **migration** diagrams | Yes | Transition path changes |
| Consolidated dependency / gap-solution matrices | Yes | New dependencies found in F |
| Transition Architecture views | Identified | Refined in F |

### Phase F — Migration Planning
| Example artifact | Produced / finalized flavor | Updated when… |
|------------------|----------------------------|----------------|
| Architecture Roadmap diagrams / timelines | Finalized visuals | Re-prioritization |
| Migration / transition diagrams | Refined | Cutover plan changes |
| Implementation & Migration Plan supporting views | Finalized | Funding/risk changes |

### Phase G — Implementation Governance
| Example artifact | Produced | Updated when… |
|------------------|----------|----------------|
| Compliance assessment reports / checklists (assessment artifacts) | Yes | Re-review after remediation |
| Exception / waiver records (often with Governance Log) | Yes | New exceptions |

### Phase H — Architecture Change Management
| Example artifact | Produced / updated | Circumstances |
|------------------|-------------------|---------------|
| Impact diagrams / updated landscape snapshots | As needed | External or internal change drivers |
| Updates to earlier catalogs/matrices/diagrams | Yes | Approved architecture change |

---

## When are artifacts updated? (reference circumstances)

| Circumstance | What happens |
|--------------|--------------|
| **Baseline → Target development** | Create/update domain artifacts in **B/C/D** |
| **Gap analysis results** | Update models to show gaps; feed **E** solution grouping |
| **Iteration** | Later phase discovery forces revisit of earlier artifacts |
| **Requirements change** | **Requirements Impact Assessment** → update ARS and related artifacts |
| **Transition Architecture defined** | Add intermediate-state views (**E/F**) |
| **Standards change** | Update tech/data standards-related catalogs; may touch continuum/SIB |
| **Compliance finding** | May require artifact/delivery correction or waiver documentation (**G**) |
| **Business/environment change** | **H** triggers updates or a new ADM cycle |

---

## Exam mapping drills

1. Business process diagram first built in detail → **Phase B**  
2. Application communication diagram → **Phase C** (Applications)  
3. Network / platform diagram → **Phase D**  
4. First strong focus on migration/transition diagrams → **E** (refine **F**)  
5. Stakeholder map → **Phase A**  
6. Catalog inside ADD → still an **artifact**; ADD is the **deliverable**  
7. Artifact updated because a requirement changed mid-cycle → **Requirements Management** impact path  

---

## Mini scenario prompts

| Stem | Best answer flavor |
|------|-------------------|
| “We need a matrix of applications to business units” | **Application Architecture artifact (Phase C)** |
| “Show the as-is and to-be business process” | **Business diagrams (Phase B)** |
| “Show how work packages move over time to the target” | **Roadmap / migration artifacts (E→F)** |
| “Document entities and which functions use them” | **Data catalog + matrix (Phase C Data)** |
| “Capture who the stakeholders are and their concerns” | **Stakeholder map (Phase A)** |
