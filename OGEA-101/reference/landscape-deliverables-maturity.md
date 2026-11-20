# Landscape levels, BA concepts, deliverables, maturity vs compliance

**Exam weight:** High for **distinctions** (which level / which deliverable / compliance vs maturity). Recognition only — not deep modeling.

---

## 1. Architecture Landscape levels

| Level | Meaning | Exam hooks |
|-------|---------|------------|
| **Strategic Architecture** | Broad, **enterprise-level** direction over a **longer** planning horizon | Enterprise-wide, long horizon |
| **Segment Architecture** | A major **business segment**, domain, or related collection of **programs** | Segment / domain / program cluster |
| **Capability Architecture** | A **focused** capability or **specific solution-related** change | Narrow scope, one capability / solution |

**Trap:** Do not confuse **Capability Architecture** (landscape breadth) with **Architecture Capability** (the EA team’s ability to run EA — repository area / Preliminary).

### What is provided, to whom (exam + practical)

Think: **breadth ↓ → detail ↑**. Strategic answers “where is the enterprise going?” Segment answers “how does this domain/program portfolio change?” Capability answers “what must this specific change look like to build?”

| Level | What is typically provided | Primary audience (to whom) | Simple example |
|-------|----------------------------|----------------------------|----------------|
| **Strategic Architecture** | Enterprise **direction**: major outcomes, capability themes, principles alignment, long-horizon target shape, investment priorities — **not** project designs | **CxO / board / strategy**, enterprise architects, portfolio leadership | “In 5 years we become a digital lender: shared customer platform, cloud-first, risk capability standardized bank-wide.” |
| **Segment Architecture** | Architecture for a **business segment or domain** (or related **programs**): segment baseline/target, major building blocks, program-level roadmap, dependencies across projects in that segment | **Segment / domain owners**, program directors, domain architects, business unit leadership | “Retail Banking segment: Target for onboarding + payments programs; shared KYC services; 3-year segment roadmap.” |
| **Capability Architecture** | Architecture for **one capability or solution change**: detailed enough baseline/target, views, requirements, and solution constraints for **delivery** | **Project / product / solution teams**, capability owners, delivery architects, vendors implementing the change | “Credit Risk Assessment capability: Target process, data entities, applications, and integration for the new scoring solution.” |

**Audience ladder (simple)**

- Strategic → **enterprise decision-makers** (“Should we invest this way?”)  
- Segment → **domain / program leaders** (“How do our programs fit together?”)  
- Capability → **delivery teams** (“What exactly do we build for this change?”)

**Banking example (one story across levels)**

1. **Strategic:** Digitize lending enterprise-wide over 5 years.  
2. **Segment:** Mortgage & personal-loan domain architecture and program set.  
3. **Capability:** “Mortgage underwriting decision” capability architecture for the next release.

**Exam stems**

- Long horizon + whole enterprise → **Strategic**  
- Business unit / domain / related programs → **Segment**  
- Single capability or specific solution change → **Capability Architecture**

---

## 2. Business capability vs value stream

| Term | Meaning | Example flavor |
|------|---------|----------------|
| **Business capability** | **What** the organization has the **ability to do** | Credit Risk Assessment |
| **Value stream** | **How** value is delivered to a stakeholder through **value-creating stages** | Mortgage application → lending decision |

**Remember**

- Capability = **what** the business can do.  
- Value stream = **how** stakeholder value is created.  
- Capabilities are **not** simply organizational departments.  
- Value streams are **not** application interfaces.

---

## 3. Key architecture deliverables (don’t swap them)

**First:** Deliverable ≠ Artifact — formal signed **package** vs granular **catalog/matrix/diagram** inside it. See [artifacts-vs-deliverables.md](artifacts-vs-deliverables.md).

| Deliverable | What it consolidates / does |
|-------------|-----------------------------|
| **Architecture Definition Document (ADD)** | Consolidates **Baseline** and **Target** Architecture descriptions, including relevant **views** and supporting **analysis**. |
| **Architecture Requirements Specification** | Captures the **detailed requirements** and **constraints**. |
| **Architecture Roadmap** | Describes the **planned evolution** toward the Target Architecture (timing / transition path). |
| **Architecture Contract** | Formalizes **implementation-related commitments** and **governance** expectations (Phase **G** flavor). |

**Quick elimination**

- Baseline + Target + views → **ADD**  
- Detailed requirements/constraints → **Architecture Requirements Specification**  
- Planned evolution to Target → **Roadmap**  
- Implementation commitments / conformance agreement → **Contract**

**Create / update by phase:** see [deliverable-lifecycle-by-phase.md](deliverable-lifecycle-by-phase.md)  
(**B–D draft ADD/ARS** → **E update / first full Roadmap** → **F finalize**; ADD = qualitative, ARS = quantitative.)

---

## 4. Architecture Maturity Model vs compliance review

| Concept | Measures |
|---------|----------|
| **Architecture Maturity Model** | Maturity of the **architecture capability / practice** (governance, processes, consistency, continuous improvement, etc.) — **enterprise-wide practice** assessment |
| **Compliance review / assessment** | Whether a **particular implementation** **conforms** to architecture expectations |

**Remember:** Compliance = conformance of an **implementation**. Maturity = development of the **architecture practice**. A compliance review does **not** replace an enterprise-wide maturity assessment of the EA function.
