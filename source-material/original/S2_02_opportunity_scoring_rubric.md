# AI Readiness Assessment — Opportunity Scoring Rubric
**Version 1.0 | E-Commerce / DTC Vertical**

---

## How to Use This Rubric

Apply this rubric to every Category A and Category B process identified in the Process Mapping Framework. Score each dimension 1–3. Sum for a total (6–18). Use the total to classify the process as a Tier 1, Tier 2, or Tier 3 opportunity.

| Total Score | Tier | Recommendation |
|-------------|------|----------------|
| 15–18 | 🟢 Tier 1 — Start Here | Recommend as first AI adoption candidate |
| 10–14 | 🟡 Tier 2 — Next Wave | Include in 90-day roadmap after Tier 1 |
| 6–9 | 🔴 Tier 3 — Not Yet | Document blockers; revisit in 6–12 months |

---

## The Six Dimensions

---

### Dimension 1: Time & Cost Impact
*How much does this process cost the business in time, labour, or operational expense today?*

| Score | Description |
|-------|-------------|
| 3 | High impact — process consumes significant weekly hours across multiple people, or is a known cost centre. AI adoption would produce visible time or cost savings within 30 days. |
| 2 | Medium impact — process takes meaningful time but is not a primary bottleneck. Savings would be real but not immediately felt at the business level. |
| 1 | Low impact — process is quick, infrequent, or already efficient. AI adoption would produce marginal savings that are hard to measure. |

**What to look for in discovery:**
- Hours per week spent on this process across all people involved
- Whether the process scales linearly with business growth (if yes, the cost compounds)
- Whether the team describes this process as "a lot of manual work" unprompted

---

### Dimension 2: Rule Consistency
*How consistent and rule-based is this process? Can the rules be written down?*

| Score | Description |
|-------|-------------|
| 3 | Highly consistent — the process follows clear, documentable rules in the vast majority of cases. Edge cases are rare and manageable. AI can handle 80%+ of instances reliably. |
| 2 | Mostly consistent — there is a clear core process, but meaningful exceptions exist that require judgment. AI can handle the routine portion; humans handle exceptions. |
| 1 | Highly variable — the process depends heavily on context, relationship, or judgment that cannot easily be encoded. AI adoption here is premature. |

**What to look for in discovery:**
- Can the process owner describe the steps without saying "it depends" more than twice?
- Are exceptions truly rare, or do they make up 30%+ of cases?
- Has anyone ever written down how this process works?

---

### Dimension 3: Data Readiness
*Is the data that feeds this process available, structured, and clean enough for AI to work with?*

| Score | Description |
|-------|-------------|
| 3 | Data is structured, accessible, and reasonably clean. It lives in a system that can connect to AI tooling. No major remediation needed before adoption. |
| 2 | Data exists but has quality issues or lives in systems that require integration work before AI can access it. Adoption is possible but requires a data prep step first. |
| 1 | Data is unstructured, incomplete, siloed, or inaccessible. AI cannot work with it in its current state. Significant remediation required before any adoption is viable. |

**What to look for in discovery:**
- Where does the data live? (Spreadsheet, CRM, ERP, email inbox?)
- When was it last cleaned or audited?
- Does it have consistent formatting and naming conventions?

---

### Dimension 4: Error & Rework Cost
*What is the cost of errors in this process today — and what would the cost be if AI produced errors at scale?*

| Score | Description |
|-------|-------------|
| 3 | Current errors are costly (returns, customer complaints, revenue loss, rework hours) AND AI errors at scale would be catchable before causing major damage. High upside, manageable downside. |
| 2 | Current errors are moderate. AI errors would be noticeable but not catastrophic. Net improvement likely even with imperfect AI accuracy. |
| 1 | Either current errors are negligible (low upside) OR AI errors at scale would be damaging and hard to catch (high downside). Not a strong candidate. |

**What to look for in discovery:**
- Has this process caused a visible incident in the last 12 months?
- Is there a human checkpoint between the process output and the customer or revenue impact?
- Would the team know quickly if AI produced a wrong output?

---

### Dimension 5: Ownership & Change Readiness
*Is there a named owner for this process, and is that person open to change?*

| Score | Description |
|-------|-------------|
| 3 | Clear named owner who is engaged, understands the process deeply, and is motivated to improve it. Team is generally open to new tools and workflows. |
| 2 | Process has an informal owner or shared ownership. Some openness to change, but adoption will require active change management. |
| 1 | No clear owner, or owner is resistant to change. Process is tribal knowledge. AI adoption here will stall without significant internal work first. |

**What to look for in discovery:**
- Who specifically owns this process? Ask for a name, not a team.
- Is that person in the room (or on the call)?
- Has this process been changed or improved in the last 12 months?

---

### Dimension 6: Integration Feasibility
*How hard is it to connect an AI tool to this process given the current tech stack?*

| Score | Description |
|-------|-------------|
| 3 | The relevant systems have APIs or native integrations with mainstream AI tools. No-code or low-code connection is feasible. Time to first working integration: days to weeks. |
| 2 | Integration is possible but requires some technical work — API configuration, data mapping, or middleware setup. Feasible within a standard project timeline. |
| 1 | Integration requires significant custom development, legacy system access, or vendor cooperation that is uncertain. Not viable without dedicated engineering resources. |

**What to look for in discovery:**
- What tools are currently used in this process? (Shopify, Klaviyo, Gorgias, etc.)
- Does the company have a developer or technical resource available?
- Have they successfully integrated tools before?

---

## Scoring Sheet Template

**Client:** _______________
**Assessment Date:** _______________
**Auditor:** _______________

| Process | D1: Time/Cost | D2: Rule Consistency | D3: Data Readiness | D4: Error Cost | D5: Ownership | D6: Integration | Total | Tier |
|---------|--------------|--------------------|--------------------|---------------|--------------|----------------|-------|------|
| | | | | | | | | |
| | | | | | | | | |
| | | | | | | | | |
| | | | | | | | | |
| | | | | | | | | |

---

## Interpretation Guide

**Tier 1 processes (15–18)**
These are your first AI adoption recommendations. Include in the executive summary as the primary finding. For each, specify the recommended tool or approach, the data preparation required, the expected outcome, and a suggested owner. These become the core of the 30/60/90-day action plan.

**Tier 2 processes (10–14)**
Include these in the roadmap but position them as the second wave — after Tier 1 adoptions are stable and producing results. This is important: companies that try to adopt AI across multiple processes simultaneously almost always fail. Sequence matters.

**Tier 3 processes (6–9)**
Document these explicitly with the reason for the low score. This is not a failure finding — it is a clarity finding. Clients find it genuinely useful to know what not to pursue. For each Tier 3 process, include a "what needs to change before this becomes viable" note.

---

## Aggregate Readiness Profile

After scoring all processes, produce a dimension-level aggregate view:

| Dimension | Average Score | Interpretation |
|-----------|---------------|---------------|
| Time & Cost Impact | | |
| Rule Consistency | | |
| Data Readiness | | |
| Error & Rework Cost | | |
| Ownership & Change Readiness | | |
| Integration Feasibility | | |

**The two dimensions that most often reveal systemic blockers:**

- **Data Readiness averaging below 2.0** means the company is not ready to adopt AI anywhere at scale. The first recommendation becomes a data hygiene and infrastructure project, not an AI tool. Say this clearly.
- **Ownership averaging below 2.0** means the organizational design will defeat any AI adoption regardless of technical feasibility. The recommendation becomes a change management and accountability conversation before any tooling decision.

---

## Version Notes
- v1.0: E-commerce / DTC baseline (6 dimensions)
- Healthcare RCM variant to add: Compliance Readiness and Audit Trail dimensions
- Legal variant to add: Privilege and Confidentiality dimensions
