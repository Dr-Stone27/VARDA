# AI Workflow Audit — Scoring Rubric
**Version 1.0 | E-Commerce / DTC Vertical**

---

## How to Use This Rubric

Apply this rubric to each AI touchpoint identified during the audit. A "touchpoint" is any point in the client's operation where an AI tool produces an output that feeds into a business process or customer-facing system.

Score each dimension 1–3. Sum the scores for a touchpoint total (5–15). Use the total to classify the touchpoint as Green, Amber, or Red.

| Total Score | Classification | Action |
|-------------|---------------|--------|
| 13–15 | 🟢 Green — Healthy | Monitor only |
| 9–12 | 🟡 Amber — At Risk | Recommend fixes in 60 days |
| 5–8 | 🔴 Red — Critical | Prioritize immediately |

---

## The Five Dimensions

---

### Dimension 1: Data Quality
*What is the AI tool working with? Is the input reliable enough to produce trustworthy output?*

| Score | Description |
|-------|-------------|
| 3 | Input data is clean, consistent, and regularly validated. Schema is documented. Edge cases are handled. |
| 2 | Input data is mostly clean but has known gaps or inconsistencies that are not systematically addressed. |
| 1 | Input data is noisy, inconsistent, or poorly structured. No validation process exists. AI is amplifying bad data. |

**E-commerce signals to look for:**
- Product metadata completeness and consistency across SKUs
- How pricing data is sourced and how often it is updated
- Whether customer data feeding personalization tools has been deduplicated

---

### Dimension 2: Human Oversight
*Where does a human check the AI's output before it affects a customer or a business process?*

| Score | Description |
|-------|-------------|
| 3 | Clear human review gate exists. A named role owns verification. Review criteria are documented. |
| 2 | Informal review exists but is inconsistent — depends on individual initiative, not process. |
| 1 | No human review. AI output feeds directly into production, customer-facing systems, or downstream automation without verification. |

**E-commerce signals to look for:**
- Whether AI-generated product descriptions are reviewed before publishing
- Whether dynamic pricing outputs are checked before going live
- Whether AI-drafted marketing copy has a brand review step

---

### Dimension 3: Fallback Logic
*What happens when the AI gets it wrong or produces no output? Is there a defined recovery path?*

| Score | Description |
|-------|-------------|
| 3 | Fallback is documented and tested. System degrades gracefully — defaults to a safe state or routes to a human. |
| 2 | Informal fallback exists (someone usually catches it) but it is not documented or consistently applied. |
| 1 | No fallback. When the AI fails, the process either breaks, produces a bad output silently, or requires emergency intervention. |

**E-commerce signals to look for:**
- What happens when the personalization engine returns no recommendation
- What happens when dynamic pricing logic errors on a SKU
- Whether AI chatbot failures route to a human agent or dead-end

---

### Dimension 4: Output Verification
*Is there a mechanism to check whether the AI's output was actually correct — after the fact?*

| Score | Description |
|-------|-------------|
| 3 | Output quality is tracked with a defined metric (accuracy rate, error rate, conversion impact). Results are reviewed regularly. |
| 2 | Some tracking exists but it is ad hoc — reviewed only when a problem surfaces, not proactively. |
| 1 | No tracking. There is no way to know whether the AI is performing well or degrading over time without a visible incident. |

**E-commerce signals to look for:**
- Whether AI recommendation quality is tracked against conversion or return rates
- Whether AI-generated content is A/B tested against baseline
- Whether pricing errors have been caught retroactively after customer complaints

---

### Dimension 5: Team Awareness
*Does the team understand what the AI tool is doing, its limitations, and when not to trust it?*

| Score | Description |
|-------|-------------|
| 3 | Team has been trained on the tool's limitations. There is shared understanding of when to override the AI. Escalation path is clear. |
| 2 | Some team members understand the tool well; others use it without understanding failure modes. Knowledge is uneven. |
| 1 | Tool was adopted quickly. Most users treat it as a black box. No training has occurred. Nobody owns it formally. |

**E-commerce signals to look for:**
- Whether the team knows what data the personalization tool is trained on
- Whether marketing team understands what prompts produce off-brand output
- Whether there is a named owner for each AI tool in the stack

---

## Scoring Sheet Template

**Client:** _______________
**Audit Date:** _______________
**Auditor:** _______________

| AI Touchpoint | D1: Data Quality | D2: Human Oversight | D3: Fallback Logic | D4: Output Verification | D5: Team Awareness | Total | Classification |
|---------------|-----------------|--------------------|--------------------|------------------------|-------------------|-------|---------------|
| [Tool / Workflow] | | | | | | | |
| [Tool / Workflow] | | | | | | | |
| [Tool / Workflow] | | | | | | | |
| [Tool / Workflow] | | | | | | | |
| [Tool / Workflow] | | | | | | | |

---

## Interpretation Guide

**When a touchpoint scores Red (5–8)**
This is a live risk. Document the specific failure mode, estimate the business impact (revenue leakage, customer experience degradation, compliance exposure), and flag it as a Priority 1 fix in the deliverable.

**When a touchpoint scores Amber (9–12)**
This is a managed risk that will likely become a problem at scale. Include it in the 60-day pilot plan with a clear owner and success metric.

**When a touchpoint scores Green (13–15)**
Document it as a strength. Clients find it useful to see what is working — it builds trust in the audit and makes the Red findings more credible.

---

## Aggregate Risk Profile

After scoring all touchpoints, produce an aggregate view:

| Dimension | Average Score Across All Touchpoints | Interpretation |
|-----------|--------------------------------------|---------------|
| Data Quality | | |
| Human Oversight | | |
| Fallback Logic | | |
| Output Verification | | |
| Team Awareness | | |

A dimension averaging below 2.0 across all touchpoints is a **systemic gap** — it means the problem is organizational, not tool-specific. Call this out explicitly in the executive summary. It changes the nature of the recommendation from "fix this tool" to "fix this practice."

---

## Version Notes

- v1.0: E-commerce / DTC baseline
- Next versions to build: Healthcare RCM variant (adds Compliance and Audit Trail dimensions), Legal variant (adds Citation Accuracy and Privilege dimensions)
