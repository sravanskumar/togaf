# Exam examples gallery (OGEA-101)

Concrete **examples** for high-yield terms. Use with definitions in `02`, `phases/`, and other reference notes.  
**Rule:** Examples help recognition; official wording still comes from the **TOGAF Standard, 10th Edition**.

---

## 1. ADM phases (one situation each)

| Phase | Example situation |
|-------|-------------------|
| **Preliminary** | Bank has no EA team, no principles, no agreed ADM tailoring — “set up how we do architecture.” |
| **A** | Sponsors approve a Vision and Statement of Architecture Work to digitize lending. |
| **B** | Model baseline/target mortgage underwriting processes and business capabilities. |
| **C** | Define customer/loan data entities and the applications that own them. |
| **D** | Decide target platforms, network zones, and tech standards for the lending stack. |
| **E** | Group gaps into work packages: “KYC platform”, “Decision engine”, “Servicing portal”. |
| **F** | Sequence those packages over 8 quarters on a finalized Architecture Roadmap. |
| **G** | Vendor build reviewed against architecture; Architecture Contract signed; compliance checks. |
| **H** | New regulation changes capital rules → architecture change cycle / new Request for Architecture Work. |
| **Requirements Management** | Mid-cycle: residency rule changes → Requirements Impact Assessment updates ARS. |

---

## 2. Stakeholder / concern / viewpoint / view

| Term | Example |
|------|---------|
| **Stakeholder** | Chief Risk Officer; Head of Retail Banking; External regulator |
| **Concern** | “Can we prove credit decisions are auditable?”; “Cost of change”; “Time-to-yes for applicants” |
| **Viewpoint** | “Security viewpoint” conventions: which diagrams, language, and concerns for security auditors |
| **View** | The actual security diagram pack produced for those auditors using that viewpoint |

---

## 3. ABB vs SBB

| Term | Example |
|------|---------|
| **ABB** | Logical building block: “Customer Identity & Access” capability/behavior |
| **SBB** | Okta / Azure AD tenant (or chosen IAM product) that **implements** that ABB |
| Pair | ABB “Payments Orchestration” → SBB “Vendor X payment hub” |

---

## 4. Deliverable vs artifact vs building block

| Term | Example |
|------|---------|
| **Deliverable** | Signed **Architecture Definition Document** for the lending program |
| **Artifact** | Application portfolio **catalog**; app-to-org **matrix**; process **diagram** inside the ADD |
| **Building Block** | ABB/SBB “Document Generation” (capability chunk — not the whole signed ADD) |

---

## 5. Continuum

| Point on continuum | Example |
|--------------------|---------|
| **Foundation** | Generic TRM-style foundation architecture concepts |
| **Common Systems** | Common security / integration patterns used across many industries |
| **Industry** | Banking industry reference architecture for lending |
| **Organization-Specific** | *This bank’s* tailored lending target architecture and standards |

---

## 6. Architecture Repository areas

| Area | Example content |
|------|-----------------|
| **Architecture Metamodel** | Org’s agreed entities/relationships for describing architectures |
| **Architecture Capability** | EA org chart, roles (Lead EA, Domain Architect), skills matrix |
| **Architecture Landscape** | Strategic 5-year digital landscape + segment maps for Retail/Corporate |
| **Standards Information Base** | “Must use enterprise API gateway”; approved OS/DB list |
| **Reference Library** | Reference models, ADM templates, integration patterns library |
| **Governance Log** | Board decision: exception granted for legacy core until 2027 |
| **Architecture Requirements Repository** | Residency, SLA, audit, interoperability requirements for lending |

---

## 7. Architecture principle (full N-S-R-I mini example)

| Part | Example |
|------|---------|
| **Name** | Buy over Build |
| **Statement** | Prefer acquiring proven products/services before custom development when they meet requirements. |
| **Rationale** | Faster time-to-market; lower long-term support cost; focus scarce talent on differentiating capabilities. |
| **Implications** | RFP process required; architecture review of SaaS fit; integration via standard patterns; exceptions need Architecture Board approval. |

---

## 8. Landscape levels (audience + example)

| Level | Provide what / to whom | Example |
|-------|------------------------|---------|
| **Strategic** | Enterprise direction → CxO | 5-year digital lender strategy |
| **Segment** | Domain/programs → segment leaders | Retail Banking onboarding + payments programs |
| **Capability** | Focused change → delivery team | Credit Risk Assessment scoring solution architecture |

---

## 9. Business capability vs value stream

| Term | Example |
|------|---------|
| **Capability** | Credit Risk Assessment; Customer Onboarding; Collections |
| **Value stream** | Apply → Verify → Decide → Disburse (mortgage journey) |
| Trap | Capability ≠ “Risk Department”; value stream ≠ “the mobile app UI” |

---

## 10. Key deliverables

| Deliverable | Example content / use |
|-------------|----------------------|
| **Architecture Vision** | One-pager + high-level target for “digital lending in 18 months” for sponsors |
| **ADD** | Baseline/target business/data/app/tech descriptions + key views for the program |
| **ARS** | “99.9% availability”; “Region X residency”; “mandatory enterprise IAM” |
| **Architecture Roadmap** | Q1 KYC → Q3 Decision engine → Q5 Servicing on a timeline |
| **Architecture Contract** | Agreement that Vendor Y must implement named ABBs and pass compliance reviews |
| **Implementation & Migration Plan** | Detailed cutovers, owners, costs, and transition states for F |

---

## 11. Architecture requirements vs backlog

| Architecture requirement | Backlog feature (not ARS focus) |
|--------------------------|--------------------------------|
| Data residency Region X | Upload profile photo |
| Mandatory enterprise identity | Forgot-password link |
| 99.9% availability | Fix CSS on login |
| API gateway only | One-off point-to-point script |
| Audit all credit decisions | Show green checkmark on submit |

(More: [../phases/requirements-management.md](../phases/requirements-management.md))

---

## 12. Techniques

| Technique | Example situation |
|-----------|-------------------|
| **Gap analysis** | Target needs real-time decisioning; baseline has overnight batch → gap |
| **Compliance assessment** | Vendor delivery reviewed against ADD/ARS in Phase G |
| **Maturity Model** | Score how mature EA governance/process is enterprise-wide |
| **Business scenario** | “First-time buyer applies for mortgage online” to surface stakeholders/concerns |
| **Requirements Impact Assessment** | New residency law mid-cycle → impact on data/app architecture |
| **Stakeholder mapping** | Plot CRO vs CIO vs regulator interest/influence |
| **Transformation readiness** | Assess whether ops/culture can absorb simultaneous KYC + core change |
| **Trade-off analysis** | Faster cloud SaaS vs stricter data residency control |
| **Initial risk** | Migration outage risk rated High **before** dual-run/rollback plan |
| **Residual risk** | Same risk rated Medium **after** mitigations; governance accepts it |

---

## 13. Governance

| Term | Example |
|------|---------|
| **Architecture Board** | Approves exception to keep legacy payments hub 18 more months |
| **Compliance assessment** | Project scored “non-conformant” on identity integration → remediation |
| **Architecture Contract** | Delivery partner commits to gateway + audit requirements before go-live |
| **Change Request** | “Add new bureau feed” raised during build → assessed for architecture impact |

---

## 14. Maturity vs compliance (contrast)

| | Example question answered |
|--|---------------------------|
| **Maturity** | “How developed is our EA practice (process, governance, skills)?” |
| **Compliance** | “Did *this* payments project implement the agreed architecture?” |

---

## 15. Preliminary vs Phase A (contrast)

| | Example |
|--|---------|
| **Preliminary** | Hire Lead EA, publish principles, tailor ADM, stand up repository |
| **Phase A** | For *this* lending initiative: Vision, stakeholders, SoAW approval |

**EA “Architecture Charter” (practice):** mandate/scope/authority for the EA function ≈ **Organizational Model + governance** from **Preliminary**.  
**SoAW (exam):** agreement to proceed with **this** cycle in **Phase A** — different document.

---

## Quick self-check

1. Okta implementing “Customer Identity” ABB → **SBB**  
2. App-to-org matrix inside ADD → **Artifact**  
3. Signed Roadmap document → **Deliverable**  
4. “Buy over Build” implications = budget/RFP/exception process → **Implications** part of principle  
5. Retail Banking programs architecture → **Segment**  
6. Vendor conformance check → **Compliance (G)**, not maturity  
