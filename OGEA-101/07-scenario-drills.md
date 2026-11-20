# OGEA-101 — Scenario-style drills (situational stems)

**Important:** Foundation (OGEA-101) is still **simple multiple-choice**, not Part 2’s 8 complex gradient scenarios.  
But many Part 1 questions are **mini-scenarios**: a short situation + “which phase / deliverable / concept?”

This file trains that skill: **read the story → spot the keyword → map to the TOGAF concept**.

---

## How to attack a scenario stem (60-second method)

1. **Ignore fluff** (company name, industry noise).  
2. **Underline the ask:** phase? deliverable? repository area? landscape level? artifact vs deliverable?  
3. **Match one keyword cluster** (table below).  
4. **Eliminate** options that belong to a neighboring concept (E vs F, Preliminary vs A, ADD vs Roadmap, maturity vs compliance).  
5. If two remain, pick the one that matches **TOGAF vocabulary**, not real-world habit.

### Keyword → concept cheat map

| If the story mentions… | Lean toward… |
|------------------------|--------------|
| Set up EA team, principles, framework, “how we do architecture here” | **Preliminary** |
| Stakeholders agree vision, approve Statement of Architecture Work, proceed | **Phase A** |
| Business processes / capabilities / org baseline-target | **Phase B** |
| Data entities + applications | **Phase C** |
| Platforms, tech standards, infrastructure | **Phase D** |
| Group gaps into work packages / first complete roadmap | **Phase E** |
| Finalize timeline / migration plan / roadmap timing | **Phase F** |
| Project must conform; sign contract; compliance assessment | **Phase G** |
| Environment changed; update architecture; new cycle request | **Phase H** |
| Continuous requirements / impact of requirement change | **Requirements Management** |
| Baseline + target + views in one formal document | **ADD** |
| Measurable criteria / quantitative requirements | **ARS** |
| Residency, SLA, mandatory API gateway / identity, audit logging | **Architecture requirement** (not a UI user story) |
| Work packages on a timeline toward target | **Architecture Roadmap** |
| Implementation commitments between governance and delivery | **Architecture Contract** |
| Catalog / matrix / diagram | **Artifact** |
| Signed formal package (Vision, ADD, Roadmap…) | **Deliverable** |
| Logical reusable capability | **ABB** |
| Vendor product / real component | **SBB** |
| Whole enterprise, long horizon | **Strategic Architecture** |
| Business unit / domain / related programs | **Segment Architecture** |
| One capability or specific solution change | **Capability Architecture** |
| What business can do | **Business capability** |
| How stakeholder value is created end-to-end | **Value stream** |
| Patterns, templates, reference models in the repo | **Reference Library** |
| Standards catalog | **Standards Information Base** |
| Governance decisions / compliance outcomes logged | **Governance Log** |
| EA practice maturity across the org | **Maturity Model** |
| Did this project conform? | **Compliance assessment** |
| Name / Statement / Rationale / Implications | **Principle template** |
| Baseline vs target — what’s missing? | **Gap analysis** (B/C/D → feeds E) |
| Org readiness for transformation | **Business Transformation Readiness Assessment** |
| Requirement changed — assess impact | **Requirements Impact Assessment** |
| Who are stakeholders / concerns? | **Stakeholder mapping** |
| Consolidate gaps + solutions + dependencies | **Phase E** technique / matrices |

Full technique sheet: [reference/techniques-cheat-sheet.md](reference/techniques-cheat-sheet.md).

---

## Practice scenarios (answer after each block; key at end)

### Set A — ADM phase scenarios

**S1.** A bank has no EA team, no architecture principles, and no agreed method. Leadership wants to “start doing TOGAF properly.” Which phase addresses this first?  
A) Phase A  
B) Preliminary  
C) Phase H  
D) Phase G  

**S2.** Stakeholders have agreed a high-level target picture and signed the Statement of Architecture Work to continue. Which phase just completed its main job?  
A) Preliminary  
B) Phase A  
C) Phase E  
D) Phase F  

**S3.** Architects finished Business, Data, Application, and Technology baseline/target work. They now group gaps into major work packages and produce the first complete Architecture Roadmap. Which phase?  
A) Phase D  
B) Phase E  
C) Phase F  
D) Phase G  

**S4.** The PMO needs a finalized time-phased migration plan and a finalized Architecture Roadmap before funding releases. Which phase?  
A) Phase E  
B) Phase F  
C) Phase G  
D) Phase B  

**S5.** A vendor is building a system. EA must ensure the build matches the agreed architecture and signs an Architecture Contract; compliance reviews are scheduled. Which phase?  
A) Phase F  
B) Phase G  
C) Phase H  
D) Phase A  

**S6.** After go-live, a regulation changes the operating model. EA monitors the impact and may issue a new Request for Architecture Work. Which phase?  
A) Phase G  
B) Phase H  
C) Preliminary  
D) Phase E  

### Set B — Deliverable / artifact scenarios

**S7.** Leadership asks for one formal document that consolidates baseline and target architectures across domains, with key views and analysis. Which deliverable?  
A) Architecture Roadmap  
B) Architecture Definition Document  
C) Architecture Contract  
D) Standards Information Base  

**S8.** Implementation teams need measurable criteria and constraints they must meet to be architecture-compliant. Which deliverable?  
A) Architecture Vision  
B) Architecture Requirements Specification  
C) Architecture Continuum  
D) Reference Library  

**S9.** A program board wants work packages laid out on a timeline from baseline to target, including transition states. Which deliverable?  
A) Architecture Roadmap  
B) Architecture Contract  
C) Architecture Metamodel  
D) Viewpoint  

**S10.** Inside the ADD, there is an application/organization matrix and a process diagram. Those matrix and diagram are best classified as?  
A) Deliverables  
B) Architecture Contracts  
C) Artifacts  
D) Architecture Principles  

**S11.** EA prepares a formal agreement with the delivery partner covering scope, conformance measures, and acceptance. Which deliverable?  
A) Architecture Roadmap  
B) Architecture Contract  
C) Business Scenario  
D) Architecture Landscape  

### Set C — Landscape / BA / repository / governance scenarios

**S12.** The CEO wants a 5-year enterprise digital direction — shared platforms and investment themes, not project designs. Which landscape level?  
A) Capability Architecture  
B) Segment Architecture  
C) Strategic Architecture  
D) Solutions Continuum  

**S13.** Retail Banking leadership needs architecture covering onboarding and payments programs together for that business domain. Which landscape level?  
A) Strategic Architecture  
B) Segment Architecture  
C) Capability Architecture  
D) Architecture Capability  

**S14.** A delivery team needs architecture detail for the “Credit Risk Assessment” solution change starting next sprint. Which landscape level?  
A) Strategic Architecture  
B) Segment Architecture  
C) Capability Architecture  
D) Preliminary  

**S15.** A BA says “Credit Risk Assessment is what we can do”; another says “Application → decision → disbursement is how the customer gets value.” Which pair is correct?  
A) Capability = value stream; value stream = department  
B) Capability = what business can do; value stream = how stakeholder value is created  
C) Capability = application UI; value stream = ABB  
D) Both are Architecture Contracts  

**S16.** An architect stores reusable patterns and reference models for others to copy. Which Architecture Repository area?  
A) Governance Log  
B) Standards Information Base  
C) Reference Library  
D) Architecture Requirements Repository  

**S17.** Mandatory technology and data standards the organization must follow are catalogued where?  
A) Reference Library  
B) Standards Information Base  
C) Architecture Landscape  
D) Architecture Vision  

**S18.** A project claims it followed the architecture. EA runs a review of that implementation’s conformance. This is primarily?  
A) Architecture Maturity Model assessment  
B) Compliance assessment  
C) Business scenario  
D) Continuum classification  

**S19.** Leadership asks how mature the EA practice is across governance, process, and continuous improvement — not whether one project conformed. This is primarily?  
A) Compliance assessment  
B) Architecture Maturity Model  
C) Architecture Contract  
D) Gap analysis  

**S20.** A principle is written as: Name “Buy over Build”; Statement of the rule; business benefits; and required costs/activities if followed. Which template parts are these?  
A) Title, Status, Context, Decision  
B) Name, Statement, Rationale, Implications  
C) Catalog, Matrix, Diagram, View  
D) Strategic, Segment, Capability, Operational  

**S21.** A logical “Customer 360” capability is defined in architecture; Salesforce CRM is selected to implement it. Pair correctly:  
A) Salesforce = ABB; Customer 360 = SBB  
B) Customer 360 = ABB; Salesforce = SBB  
C) Both are deliverables  
D) Both are viewpoints  

**S22.** Requirements change mid-cycle after Technology Architecture work. The change must be assessed for impact across the architecture. Where does this continuous requirements handling sit?  
A) Phase D only  
B) Requirements Management (interacts with all phases)  
C) Phase G only  
D) Architecture Continuum  

---

## Answer key

| # | Ans | Why (one line) |
|---|-----|----------------|
| S1 | **B** | Standing up EA capability/principles/method = **Preliminary** |
| S2 | **B** | Vision + SoAW approval = **Phase A** |
| S3 | **B** | Work packages + first complete roadmap = **E** |
| S4 | **B** | Finalize migration timing/roadmap = **F** |
| S5 | **B** | Contract + compliance during build = **G** |
| S6 | **B** | Post-change monitoring / new cycle = **H** |
| S7 | **B** | Baseline+target+views formal package = **ADD** |
| S8 | **B** | Quantitative criteria = **ARS** |
| S9 | **A** | Timeline of work packages = **Roadmap** |
| S10 | **C** | Matrix/diagram = **artifacts** inside a deliverable |
| S11 | **B** | Implementation commitments = **Contract** |
| S12 | **C** | Enterprise long horizon = **Strategic** |
| S13 | **B** | Domain/programs = **Segment** |
| S14 | **C** | Focused solution change = **Capability Architecture** |
| S15 | **B** | Capability = what; value stream = how value is created |
| S16 | **C** | Patterns/reference models = **Reference Library** |
| S17 | **B** | Standards catalog = **Standards Information Base** |
| S18 | **B** | Implementation conformance = **compliance** |
| S19 | **B** | EA practice maturity = **Maturity Model** |
| S20 | **B** | N-S-R-I principle template |
| S21 | **B** | Logical = ABB; product = SBB |
| S22 | **B** | Requirements Management is continuous / hub |

**Score guide:** 18+/22 strong · 14–17 OK, restudy miss tags · &lt;14 revisit phases + reference notes before the timed mock.

**Miss tags:** log wrong items in [05-miss-tag-log.md](05-miss-tag-log.md) using tags like `E_vs_F`, `deliverable_vs_artifact`, `landscape_level`, `maturity_vs_compliance`.
