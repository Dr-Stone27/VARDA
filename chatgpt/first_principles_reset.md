# Varda — First-Principles Reset

**Version:** 0.1  
**Date:** 6 November 2026  
**Status:** WORKING DRAFT — not a final positioning or product decision  
**Purpose:** Reconstruct the original Varda idea, separate the enduring problem from its first proposed solutions, and define what must be learned before selecting a direction.

---

## Executive read

Varda's original work describes an AI operations advisory practice intended to help growing companies identify where AI creates value and establish the operational foundations required to sustain it. Its central thesis is that AI amplifies the conditions already present in a business: good data, clear process ownership and suitable review mechanisms can improve outcomes; weak foundations can amplify errors, inconsistency and operational risk.

The strongest enduring idea is not the DTC vertical, the Context Passport, an AI readiness score or a consulting package. It is the gap between access to AI capabilities and the ability to use those capabilities reliably inside real business workflows.

That gap is plausible and strategically relevant, but this repository does not yet contain sufficient direct customer evidence to establish its size, urgency, willingness to pay or Varda's right to win.

**Working direction:** investigate how businesses design, connect, control, evaluate and improve AI-enabled workflows. Do not assume Varda must become a generic governance platform, AI agency, software company or DTC consultancy.

## 1. What the source documents actually say

### 1.1 Original company concept

The May 2026 Company Brief positions Varda as a structured advisory practice for e-commerce and DTC brands. It proposes two services:

- **AI Workflow Audit:** examine AI touchpoints already operating in a business, identify risk and failure patterns, and deliver a prioritised fix plan.
- **AI Readiness Assessment:** map business processes before adoption, identify suitable AI opportunities, surface readiness blockers and produce a sequenced roadmap.

The stated target market is mid-market DTC/e-commerce brands, originally described as $2M–$50M ARR, with an initial prospecting focus of $2M–$20M ARR in the US and UK. The brief names legal and healthcare revenue-cycle management as possible extensions, with construction described as an early signal. These are historical targeting choices and claims, not current decisions.

### 1.2 Original operating method

The unified methodology describes five stages:

1. **Map** — establish what actually happens, not only the official process.
2. **Score** — apply defined criteria to turn observations into explainable assessments.
3. **Decide** — prioritise based on impact and feasibility.
4. **Implement** — assign owners, timelines, metrics and controls.
5. **Verify** — evaluate whether the changes produced the intended result.

The two original services use different units of analysis: existing AI touchpoints for the Workflow Audit, and operational processes for the Readiness Assessment.

### 1.3 Original philosophy

The source documents emphasise:

- Honesty over optimism.
- Process before technology.
- Specificity over superficial completeness.
- Understanding actual workflows rather than accepting official process descriptions.
- Not forcing an AI use case where AI is not appropriate.
- Delivering prioritised decisions and an actionable plan, not a generic maturity score.

### 1.4 Existing intellectual and delivery assets

The supplied documents contain a process-mapping framework, opportunity and risk rubrics, a taxonomy of failure modes and blockers, governance templates, an impact-estimation approach, sample deliverables, a Context Passport, pricing logic, prospecting material and a proposed AI-assisted delivery engine.

The systemic breakdown identifies the taxonomy as a useful distributable asset and the delivery engine / Context Passport workflow as possible productisation candidates. This is an internal assessment of the assets, not evidence of external demand.

## 2. Separate the problem from the solutions

| Level | Candidate statement | Status |
|---|---|---|
| Environmental change | AI capabilities and available tools are expanding quickly. | Broadly observable; specific claims require dated sources. |
| Underlying problem | Businesses may lack the organisational and technical capability to turn AI access into dependable workflow outcomes. | Core hypothesis; requires customer validation. |
| Problem mechanisms | Weak process definition, fragmented context, poor data, unclear ownership, insufficient permissions, weak evaluation, poor fallback and limited observability. | Mechanisms proposed by the original methodology; prevalence is unknown. |
| Possible intervention | Diagnose, redesign, connect, govern, evaluate and improve selected AI-enabled workflows. | Candidate service/product intervention. |
| Possible business models | Advisory, implementation, managed service, software, enablement or a hybrid. | Undecided. |
| Original packaging | DTC AI audits, readiness assessments and Context Passport. | Historical solution choices; not binding. |

A real underlying problem would not automatically validate any specific product, service, customer segment or price.

## 3. First-principles problem statement

**Working problem statement:**

As organisations introduce AI into operational work, they may struggle to make those systems function dependably within the surrounding business environment: the real workflow, company data and knowledge, connected applications, human decisions, permissions, exceptions and performance requirements. The resulting gap can prevent value from being realised or make failures difficult to detect, explain and correct.

This statement is deliberately broader than a product pitch. It must be narrowed through research to a specific customer, workflow and consequence.

## 4. Working thesis

**Original thesis:** “AI amplifies whatever you already have.”

**Proposed refinement for investigation:** “AI creates value only when the surrounding workflow, context, authority, integration and feedback system are designed to support it.”

The refinement does not replace the original thesis yet. It makes several factors explicit that become more important as systems move from generating suggestions to taking actions.

## 5. The system we need to understand

An AI-enabled workflow should be examined as an end-to-end system, not as a prompt or model in isolation:

1. **Business outcome** — what result is the organisation trying to achieve?
2. **Workflow** — what triggers the work, what steps occur and where does the output go?
3. **Task and decision decomposition** — which individual activities require retrieval, generation, classification, judgement, approval or execution?
4. **Context and data** — what information is required, where is the authoritative source, how current is it, and who can access it?
5. **Intelligence** — what models, agents, deterministic rules or combinations are involved?
6. **Tools and integration** — which systems can be read or changed, through what interfaces and with what permissions?
7. **Authority and human control** — what can the system decide or execute, what requires approval, and who owns exceptions?
8. **Reliability and recovery** — how is quality evaluated, failures observed, work retried, rolled back or escalated?
9. **Business feedback** — what measures establish whether the workflow improved cost, time, quality, risk, revenue or customer experience?

Controls cut across the system: access control, privacy, security, auditability, versioning, change management and accountability.

The unit of analysis may need to be the task or decision within a process, not the whole job. A process that requires human judgment can still contain bounded, automatable or augmentable activities.

## 6. Opportunity hypotheses to investigate

No hypothesis is selected. See `../01_market/opportunity_hypotheses.md` for the detailed test plan.

- **H1 — AI workflow reliability and assurance:** can businesses reliably evaluate, observe and control AI-enabled workflows in production?
- **H2 — AI integration and orchestration:** do businesses struggle to connect AI capabilities to existing workflows, systems and business outcomes?
- **H3 — Business context and knowledge infrastructure:** do businesses lack a dependable way to make accurate, current, permission-aware business context available to AI systems?
- **H0 — Incumbent sufficiency:** do existing platforms, consultancies and internal teams solve these problems adequately, leaving no attractive independent opportunity?

These hypotheses can overlap. Research must determine whether buyers experience them as one problem or different problems with different owners and budgets.

## 7. Customer segment: defer the vertical decision

The historical beachhead is DTC/e-commerce because the original materials map Shopify-related processes and tools. Keep it as one test segment, not as the definition of Varda.

A more useful temporary segment lens is operational characteristics:

- AI is already used in, or is about to be introduced into, meaningful business workflows.
- Work crosses multiple tasks, people or software systems.
- Errors, delays or inconsistent execution have meaningful consequences.
- The organisation has sufficient workflow volume for improvement to matter.
- There is an identifiable owner of the workflow and a plausible buyer.
- The organisation does not already have a complete internal capability to solve the problem.

Investigate DTC alongside no more than two adjacent segments at first. Compare them using the same criteria. Do not expand to regulated sectors purely because their apparent budgets are higher; domain expertise, compliance and trust requirements can materially change feasibility.

## 8. What survives from Varda v1

**Preserve as reusable foundations:**

- The Map → Score → Decide → Implement → Verify loop.
- The discipline of mapping actual workflows before recommending technology.
- The taxonomy as a diagnostic and communication asset.
- The emphasis on ownership, review gates, fallback, measurement and periodic health checks.
- The impact-versus-feasibility prioritisation logic.
- The honest stance that some processes should not be automated.
- The structured prospect-research and outcome-led writing principles from the cold-email prompt.

**Rework rather than discard:**

- The unit of analysis: extend from AI touchpoints / business processes to task-level, end-to-end AI-enabled workflows.
- The risk rubric: consider model/agent behaviour, delegated authority, tool permissions, evaluation, observability, change and recovery where relevant.
- The readiness rubric: distinguish technical readiness from workflow suitability and organisational readiness.
- The Context Passport: retain the discovery questions, but do not assume a static paste-ready document is a durable standalone product.
- The implementation boundary: investigate whether Varda should own a bounded pilot or implementation outcome rather than stopping at recommendations.

**Do not treat as validated:**

- The $2M–$50M DTC target, $2M–$20M initial prospect band, US/UK focus or adjacent vertical rankings.
- The stated market adoption percentages and engagement-price ranges in the company brief.
- The proposed service prices and commercial funnel.
- The $100 Context Passport price or the claim that the marketplace gap supports it.
- The scoring cut-offs and rubrics as calibrated predictors of business outcomes.
- The proposed $5,000 engagement / productisation path as a proven customer proposition.

## 9. Critical unknowns

1. Which specific workflow problem is urgent enough for a buyer to fund now?
2. Who experiences it and who controls the budget?
3. How often does it happen, and what is the measurable consequence?
4. What do customers use today: native platform features, internal engineers, agencies, consultants, observability/evaluation tools or manual work?
5. What is still missing after using those alternatives?
6. Is the gap primarily technical, operational, organisational or a combination?
7. Does the customer need diagnosis, implementation, ongoing assurance or software?
8. What data and system access would a solution require?
9. What trust, privacy, security and liability expectations apply?
10. Can Varda credibly deliver a valuable first outcome with its current founder capabilities and available time?
11. Is the problem repeated across enough customers to support a repeatable offer?
12. What would disprove the opportunity?

## 10. Evidence quality audit

The supplied company brief includes market adoption and price-range claims but does not, in the copy provided, include enough underlying source information to independently verify them. These claims must be sourced or removed before external use.

The market-validation document examines a narrow class of self-serve prompt/context products. It does not establish market demand for the core advisory offer. The sample deliverables are illustrative, not customer case studies. The scoring rubrics are structured hypotheses, not proven measurement instruments. The source brief describes the practice as pre-revenue.

External AI news and market reports discussed in prior conversations must be re-verified against original, dated sources before they are used in a formal market thesis.

## 11. Research and decision sequence

### November — opportunity discovery and solution definition

- Re-verify the current AI landscape: capabilities, agent platforms, workflow tooling, evaluation/observability, security and incumbent offerings.
- Build a competitor/substitute map around customer jobs, not product labels alone.
- Interview potential buyers and operators about actual workflows and recent failures or bottlenecks.
- Compare DTC with a small number of adjacent segments.
- Record repeated problem patterns, economic consequences, current workarounds and buying authority.
- Select one customer/problem/workflow only when evidence supports it.
- Define a narrow solution hypothesis, architecture, exclusions, baseline and success criteria.

### December — build and proof

- Build/configure the smallest credible pilot for the selected workflow.
- Establish representative test cases and failure cases before evaluating.
- Define access, permission, approval, escalation and rollback boundaries.
- Compare against a baseline or current process.
- Record observed performance, failure modes, customer feedback, operational effort and limitations.
- End with a build / pivot / stop decision and a case study that distinguishes measured results from estimates.

## 12. Opportunity selection gate

Advance a candidate only when there is credible support for:

- A specific customer and workflow.
- Repeated, concrete pain from independent sources or customers.
- A meaningful business consequence.
- Evidence of urgency or existing spend/workaround.
- A clear gap in current alternatives.
- An identifiable buyer or internal champion.
- A feasible, bounded first intervention.

Do not interpret general excitement about AI as buying intent. Stronger signals include sharing workflow evidence, committing access or staff time to a pilot, introducing the budget owner, agreeing success criteria, or discussing commercial terms.

## 13. Current decision

**Decision: no market, product or business model selected.**

Proceed with discovery across H1, H2, H3 and the H0 incumbent-sufficiency hypothesis. Keep DTC as a test segment. The next deliverable is an evidence-backed opportunity map, not a product roadmap.

## Source documents

See [`source_register.md`](source_register.md) and the immutable originals under `source-material/original/`.
