# TOGAF techniques — compact exam sheet (OGEA-101)

**Depth rule:** Know **name · purpose · when (phase) · typical outcome · trap**.  
Skip full procedure manuals — Foundation tests recognition and scenario mapping, not facilitator scripts.

---

## Core techniques (MUST)

| Technique | Purpose (one line) | When (primary) | Typical outcome / “what changes” | Trap |
|-----------|--------------------|----------------|----------------------------------|------|
| **Gap analysis** | Compare **baseline vs target** to find missing/changed items | **B, C, D** (domain architectures); results feed **E** | List of **gaps** (capabilities, data, apps, tech) that must be addressed | Not a roadmap; not compliance; not maturity |
| **Architecture compliance assessment / review** | Check whether an **implementation** **conforms** to the architecture | **Phase G** (implementation governance) | Conformance findings; may trigger **remediation**, **exceptions/waivers**, **Change Requests**, contract actions | Not an enterprise EA **maturity** assessment |
| **Architecture Maturity Model** | Assess maturity of the **architecture capability/practice** | Often tied to **Preliminary** / capability improvement; used when evaluating the EA function | Scores/levels across governance, process, consistency, improvement — drives **practice** uplift | Not “did this project comply?” |
| **Business scenario** | Describe a business problem; identify stakeholders/concerns; help **scope** architecture work | Often **Phase A** (and early scoping); usable wherever problem framing is needed | Clear problem, actors, objectives, concerns → better Vision/scope | Not a substitute for B/C/D models |
| **Requirements Impact Assessment** | Assess impact when requirements **change** | **Requirements Management** (any phase) | Updated requirements understanding; may force revisiting architecture work / ARS | Not the same as gap analysis |
| **Stakeholder analysis / mapping** | Identify stakeholders, concerns, influence/interest | **Phase A** (heavily); refined later as needed | Stakeholder map → drives **viewpoints/views** and engagement | Not the Architecture Board itself |
| **Risk management (architecture)** | Identify, classify, and mitigate architecture-related risks | Across ADM; often visible in **A** and migration **E/F**; **accepted/managed under governance** | Risk categorization before/after mitigation; residual risk accepted via governance | Not compliance review; EA may identify/mitigate but governance **accepts** risk |
| **Capability-based planning** | Plan change from **business capabilities** (what we must be able to do) | Business architecture / strategy alignment (**B**, strategic planning context) | Capability gaps and prioritized capability change | Capability ≠ org chart department |

### Initial Risk vs Residual Risk (exam MUST)

TOGAF distinguishes **two levels** of risk categorization:

| Level | Meaning | Exam hook |
|-------|---------|-----------|
| **Initial Level of Risk** | Risk categorization **prior to** determining and implementing **mitigating actions** | “Before mitigation” → **Initial** |
| **Residual Level of Risk** | Risk categorization **after** implementing mitigating actions (if any) | “After mitigation” → **Residual** |

**Also remember:** The Enterprise Architect may identify risks and mitigate some, but risks must be **accepted and managed within the governance framework**.

**Example:** Risk of migration outage categorized as High (**Initial**); after dual-run and rollback plan, categorized as Medium (**Residual**); Architecture Board / governance **accepts** residual risk to proceed.

---

## Strong SHOULD (common scenario bait)

| Technique | Purpose | When | Outcome | Trap |
|-----------|---------|------|---------|------|
| **Business Transformation Readiness Assessment** | How ready is the org to absorb change? | Often **E** / migration context (also visioning inputs) | Readiness findings → sequencing, risk, migration approach | Not a tech gap analysis |
| **Interoperability assessment / requirements** | Ensure systems/org units can exchange information/services as needed | Mainly **B–D** requirements / architecture definition; checked in delivery | Interoperability requirements in ARS / architecture | Not the same as continuum classification |
| **Architecture partitioning** | Split architectures by scope/time/team/risk so work is manageable | Planning the landscape / cycle (**Preliminary**/approach; applied across ADM) | Partitioned architectures (strategic/segment/capability, etc.) | Not a deliverable name |
| **Trade-off analysis** | Balance conflicting concerns (cost, risk, performance, time) | Architecture decision-making across **B–F** | Documented trade-offs aligned to **principles** | Not gap analysis |
| **Implementation Factor Assessment & Deduction** (matrix) | Capture implementation factors and deductions that affect migration | **E / F** migration thinking | Factors feeding roadmap / migration plan | Don’t confuse with gap matrix alone |
| **Consolidated Gaps, Solutions, and Dependencies Matrix** | Consolidate gaps with candidate solutions and dependencies | **Phase E** | Input to work packages and roadmap | Phase E technique, not Phase G compliance |

---

## Related “activities” often tested as concepts (not full techniques)

| Activity / concept | When | What it does | Trap |
|--------------------|------|--------------|------|
| **Architecture Board review** | Ongoing governance; critical in **G** and principle/exception decisions | Approves direction, exceptions, compliance issues | Board ≠ maturity model |
| **Architecture Contract agreement** | Prepared **F**, used **G** | Commits delivery to architecture expectations | Not the ADD |
| **Change Request handling** | **G / H** | Triggers assessment; may start new ADM cycle | Not Preliminary setup |
| **Views / viewpoints selection** | From **A** onward as stakeholders engage | Produce **views** (artifacts) for concerns | Viewpoint = recipe; view = result |
| **Building block definition (ABB→SBB)** | Architecture definition **B–D**; solutions in **E/G** | Logical ABBs later realized as SBBs | ABB ≠ artifact catalog by itself |

---

## Scenario mapping (quick)

| Story fragment | Technique / activity |
|----------------|----------------------|
| “Finished baseline and target business/data/app/tech — what’s missing?” | **Gap analysis** |
| “Vendor build must be checked against architecture” | **Compliance assessment (G)** |
| “How mature is our EA function?” | **Maturity Model** |
| “Frame the business problem and stakeholders before Vision” | **Business scenario** |
| “A requirement changed mid-cycle — what’s the impact?” | **Requirements Impact Assessment** |
| “Who cares and what are their concerns?” | **Stakeholder mapping** |
| “Can the organization absorb this transformation?” | **Transformation readiness** |
| “Consolidate gaps into solution options and dependencies” | **Phase E matrices / work packaging** |
| “Risk level before mitigations are applied” | **Initial Level of Risk** |
| “Risk level after mitigations” | **Residual Level of Risk** |

---

## Mini drill

1. Gap analysis primary home? → **B/C/D** (feeds **E**)  
2. Compliance review primary phase? → **G**  
3. Maturity model measures? → **EA practice**, not one project  
4. Business scenario mainly helps? → **Scope / stakeholders / problem framing**  
5. Requirements change impact? → **Requirements Impact Assessment** (RM hub)  
6. Consolidated gaps + solutions + dependencies? → **Phase E**  
7. Risk categorization **before** mitigation? → **Initial**  
8. Risk categorization **after** mitigation? → **Residual**  

---

**Related files:** [landscape-deliverables-maturity.md](landscape-deliverables-maturity.md) · [deliverable-lifecycle-by-phase.md](deliverable-lifecycle-by-phase.md) · [exam-examples-gallery.md](exam-examples-gallery.md) · [07-scenario-drills.md](../07-scenario-drills.md)
