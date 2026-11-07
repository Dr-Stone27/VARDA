# Hypothesis assessment: what public evidence does and does not distinguish

**Research date:** 7 November 2026  
**Stage:** Phase 1, Stage 1D — Hypothesis testing  
**Status:** Draft for founder review; no hypothesis selected

## Purpose and boundaries

This assessment tests the available evidence for H1, H2, H3 and H0, identifies what would distinguish their primary constraints, and records the most important disconfirming evidence. It does not choose a hypothesis, customer, segment, product or service model. It uses public reports and provider documentation only; no customer interviews or workflow observation were conducted.

## Overall finding

**FACT:** Public and survey evidence supports the existence of AI adoption, technical reliability concerns in selected agent systems, reported implementation/integration friction among some enterprise respondents, and a wide range of incumbent products and services.  
**INFERENCE:** H1, H2 and H3 describe distinguishable mechanisms, but public evidence often bundles them together. A single failure can involve model behavior, missing context, permissions, integration, process design, or human oversight.  
**UNKNOWN:** The repository still has no customer-reported workflow incidents, quantified consequences, actual workaround evidence, budget/urgency data, or customer-level proof that incumbent alternatives are insufficient. Public research cannot identify a Varda opportunity or willingness to pay.

## Evidence currently relevant to testing

| ID | Source-reported observation | Evidence class and scope | Limitation for hypothesis testing |
|---|---|---|---|
| EV-010 / EV-019 | UK DSIT reports skills/expertise and accuracy/bias concerns, use in admin/marketing/IT, and implementation/embedding effort; it also reports mostly modest productivity effects, no immediate financial effect for many adopters, and low high/critical strategic importance. | FACT about self-reported results in a representative UK business survey (n=3,503; Jan–Apr 2026). | Does not isolate reliability from context/integration, measure incidents or losses, or establish who would pay. Broad UK sample, not Varda segment-specific. |
| EV-011 / EV-020 | The MAP paper reports reliability and human oversight/evaluation challenges for selected production/pilot agent systems. | FACT about a practitioner survey (306) and study sample (86 systems), with 20 case interviews; study Apr–Nov 2025. | Selected technical population, participation/geographic limitations, varying denominators; no representative prevalence, business-loss or buyer evidence. |
| EV-022–EV-027 | Cloud, evaluation, workflow, search/context and Shopify-native providers document relevant capabilities and product-specific limits. | FACT about vendor documentation, accessed 7 Nov 2026. | Capability existence is not effectiveness or customer sufficiency. Limitations are vendor-specific, not measured failure rates. |
| EV-031 | In a Publicis Sapient survey, enterprise AI decision-makers most often cited integration across systems (38%), data fragmentation (36%), governance/control (29%), and workflow integration (21%) as limits to scaling; 47% said AI was already fully capable of meeting current business needs. | CUSTOMER-REPORTED survey results; 1,550 decision-makers at companies with at least 500 employees and $100M revenue, six countries, fielded 29 Apr–14 May 2026. Publicis Sapient commissioned the survey and sells enterprise technology/services. [Report and method](https://www.publicissapient.com/resources/research/enterprise-ai-readiness-gap). | Self-reported enterprise-only survey from a provider with an interest in operational transformation. Categories can overlap and the report’s narrative favors structural explanations. Not causal evidence or representative of smaller firms. “AI can meet current needs” is not the same as alternatives solving deployment problems. |
| EV-032 | World Quality Report 2025 reports, among respondents working on GenAI in quality engineering, integration complexity (64%), data privacy risk (67%), and reliability concerns (60%); 15% reported enterprise-wide deployment while 43% were experimental and 30% had limited use cases. | CUSTOMER-REPORTED results from a survey of 2,000+ senior executives across 22 countries and 10 sectors, focused on quality engineering/testing. Report announced by OpenText with Capgemini/Sogeti, which sell related products and services. [Source and methodology](https://s23.q4cdn.com/197378439/files/doc_news/World-Quality-Report-2025-AI-adoption-surges-in-Quality-Engineering-but-enterprise-level-scaling-remains-elusive-2025.pdf). | Industry- and function-specific; survey publication is provider-sponsored; measures perceptions, not independently observed failures, losses, or willingness to pay. Not interchangeable with DSIT or Publicis Sapient samples. |

### H1 — AI workflow reliability and assurance

**What supports investigation**

- **FACT:** MAP reports reliability, human evaluation and human-in-loop operation in its selected production/pilot agent sample (EV-011/020).
- **CUSTOMER-REPORTED:** In quality-engineering contexts, WQR respondents report hallucination/reliability concerns (EV-032); DSIT respondents report accuracy/bias concerns (EV-010/019).
- **FACT:** Platform and specialist tools now document evaluation, tracing, monitoring and governance features (EV-022–EV-024), demonstrating both that the task is recognized and that substitutes exist.

**Counter-evidence and alternative explanations**

- DSIT reports only 14% of businesses consider AI highly/critically important and 64% of adopters report no immediate financial effect. That weakens an assumption of broad, urgent reliability pain (EV-019).
- 47% of Publicis Sapient survey respondents say AI is already capable of meeting current business needs; the survey also reports structural blockers rather than model capability as a common issue (EV-031). This is an enterprise-provider survey, not proof of operational reliability, but it challenges the claim that the model/tool itself is necessarily the main failure source.
- Existing evaluation and observability features may be adequate when instrumented and used well. Current evidence does not establish whether problems arise from missing tools, poor setup, unclear acceptance criteria, insufficient ownership, or genuinely inadequate capability.

**Assessment:** **Plausible technical problem; customer problem and economics UNKNOWN.** Technical evidence is stronger than the repository’s previous evidence base but not sufficient to establish prevalence, severity, budget or separate-market potential.

### H2 — AI integration and workflow orchestration

**What supports investigation**

- **CUSTOMER-REPORTED:** Publicis Sapient’s enterprise respondents cite integration, data fragmentation and workflow integration as barriers to scaling (EV-031). WQR respondents in quality engineering report integration complexity (EV-032).
- **FACT:** DSIT says time, effort and resources to implement/embed AI are reported cost barriers; it also finds most use concentrated in accessible, comparatively low-complexity tools (EV-010).
- **FACT:** Census finds that among adopting firms, 57% use AI in three or fewer functions (EV-017). This describes breadth, not whether integration failed.
- **FACT:** iPaaS, platform gateways, connectors and vertical workflow tools provide substantial substitutes (EV-022/023/026).

**Counter-evidence and alternative explanations**

- Limited functional breadth may reflect deliberate narrow use, low strategic priority, or task fit—not a failed integration project.
- Publicis Sapient’s results are enterprise-only and come from a firm that sells transformation services; WQR is focused on quality engineering and is provider-sponsored. Neither establishes smaller-business prevalence or a causal relationship between integration barriers and business losses.
- Integration friction can be caused by missing permissions, source data quality, process ambiguity, change management or lack of engineering capacity. Those causes are not equivalent and may not support the same intervention.
- Existing connectors and orchestration products are broad; the fact that integration work exists does not establish a gap in available solutions.

**Assessment:** **Reported enterprise friction; repeatable customer problem and economic significance UNKNOWN.** Current survey evidence is more directly related to H2 than H3, but cannot establish that H2 is the primary constraint in any workflow.

### H3 — Business context and knowledge infrastructure

**What supports investigation**

- **CUSTOMER-REPORTED:** Enterprise respondents cite data fragmentation (36%) as a limit to scaling in the Publicis Sapient survey (EV-031). DSIT respondents report accuracy/bias concerns (EV-010/019).
- **FACT:** Glean and other vendors document permission-aware connectors, indexing, retrieval and context features (EV-025), showing a recognized product category and available substitutes.
- **INFERENCE:** Fragmented or stale information could contribute to inaccurate outputs, but this causal pathway has not been demonstrated in Varda customer workflows.

**Counter-evidence and alternative explanations**

- Neither the Publicis Sapient nor DSIT data isolates missing/stale/permission-filtered context as the cause of errors. Data fragmentation could limit integration, analytics, governance, or human decision-making without creating an AI context-specific problem.
- Search/context vendors already document broad connector catalogs, permissions and retrieval. Their claimed capabilities challenge a generic “business context is missing” thesis; no independent evidence here shows those features fail in customers’ actual environments.
- Accuracy errors may arise from model behavior, prompt design, source quality, retrieval, process design or input ambiguity. Labeling them “context problems” before reconstructing the incident would bias discovery.

**Assessment:** **Plausible mechanism, least directly isolated in current customer-facing evidence.** There is no evidence yet that context is a primary cause rather than a correlated condition or an existing vendor category.

### H0 — Existing tools, teams and providers adequately solve the important needs

**What supports taking H0 seriously**

- **FACT:** The alternatives map documents offerings across cloud platforms, specialist tools, automation/iPaaS, enterprise search, vertical systems, consulting and managed services (EV-022–EV-028).
- **CUSTOMER-REPORTED:** In Publicis Sapient’s sample, 47% said AI was already capable of meeting current business needs (EV-031). DSIT reports broad use of free or embedded tools and relatively low strategic importance/direct spending for many firms (EV-019).
- **INFERENCE:** Some businesses may reasonably use existing features, internal staff, manual review or no action because the problem is low consequence or already adequately handled.

**Counter-evidence and alternative explanations**

- Product catalogs show available capabilities, not that customers know about them, can configure them, or get adequate outcomes. The same Publicis survey reports integration/data/governance barriers and only 18% saying AI is fully integrated enterprise-wide (EV-031).
- Provider documentation states specific connector, instrumentation and evaluation caveats (EV-022–EV-027), but no evidence establishes how often these block customers.
- Low spending or low strategic importance may indicate weak demand; alternatively it may reflect bundled features, early adoption, limited budgets or costs hidden in internal labor. Aggregate public data cannot distinguish these explanations.

**Assessment:** **Serious null hypothesis, not confirmed.** There is abundant substitute supply and some reports of adequate technology capability, but no workflow-level evidence that alternatives sufficiently solve the most important needs—or that any residual gap merits a separate venture.

## Observable distinctions for future workflow-level evidence

| If the primary constraint is… | Evidence that would support it in a concrete recent incident | What would point elsewhere |
|---|---|---|
| **H1: reliability/assurance** | Required inputs and permissions were available; integrations completed; the AI produced an incorrect, inconsistent or unsafe output/action; the failure was not caught by existing evaluation/monitoring or exception handling; a measurable human/business consequence followed. | The agent never got the needed data/tool access (H2); authoritative context was absent/stale/not retrieved (H3); the workflow had no agreed success criteria or owner (process/governance); or no consequential failure occurred. |
| **H2: integration/orchestration** | Workflow progress failed at a named system handoff, connector, authentication/permission, transformation, retry, state or ownership boundary; model behavior and required context were adequate when tested independently; the breakdown caused manual re-entry, delay or abandonment. | All systems connected and the process executed, but AI output/action was wrong (H1); inputs were unavailable/contradictory because source knowledge was missing or stale (H3); or the business chose not to integrate because the expected value was too low (H0). |
| **H3: context/knowledge** | A specific authoritative fact/policy was missing, stale, conflicting, inaccessible or not retrieved; supplying/correcting that context changes the output while the model, workflow and integration remain constant; the organization repeatedly curates or re-enters the same information. | The context was present and correctly retrieved but model reasoning/action still failed (H1); context was inaccessible because of connector/permission design (H2); or the error had no meaningful consequence and existing search/manual check is adequate (H0). |
| **H0: incumbent sufficiency/no venture** | Existing platform, internal process, provider or manual workaround handles the task end-to-end within acceptable quality, time, risk and cost; no repeated unresolved incident, active priority or change trigger is found. | Concrete recurring unresolved incidents, consequential rework/loss, failed alternatives, an identifiable owner and a credible budget/priority signal. These must be independently observed or customer-reported; general survey concerns are insufficient. |

**Important:** Causes can co-occur. Record the sequence and evidence for each incident before assigning a primary cause. A “counterfactual” test (for example, provide the missing data while leaving other variables unchanged) is a diagnostic research method, not a proposed product or implementation plan.

## Remaining assumptions and unknowns

1. **ASSUMPTION:** Survey-reported integration, context or accuracy concerns correspond to recurring incidents in a specific operational workflow.
2. **ASSUMPTION:** Any unresolved incident has a sufficiently large consequence and occurs often enough to justify action.
3. **UNKNOWN:** Who detects, owns, funds and approves work to resolve an incident; whether the user and buyer are the same person.
4. **UNKNOWN:** Whether existing tools are absent, poorly configured, blocked by access/skills, or genuinely inadequate.
5. **UNKNOWN:** Whether one primary constraint repeats across organizations, or each case is bespoke.
6. **UNKNOWN:** Whether firms would buy external help, adopt a tool, reassign internal work, or accept the status quo. Neither market surveys nor stated interest establishes willingness to pay.

## Stage 1D completion status

**Condition assessment:** H1–H3 and H0 now have explicit supporting evidence, counter-evidence, confidence limits and observable distinctions. Public evidence remains insufficient to determine customer-level primacy or commercial attractiveness, which is an explicit finding rather than a reason to select the most technically documented issue. No hypothesis or segment has been selected.

**Recommended next stage:** Stage 1E — comparative segment assessment across DTC/ecommerce, business/professional services, and software/technology, including pre-adoption, active-adoption and abandoned-adoption cases, after founder approval. Stage 1E should compare where these observable constraints may be visible; it should not claim segment-level prevalence without comparable evidence.

## Sources accessed 7 November 2026

1. DSIT 2026 AI adoption survey, [executive summary](https://www.gov.uk/government/publications/ai-adoption-survey-2026/ai-adoption-survey-report-2026-executive-summary).
2. Pan et al., [*Measuring Agents in Production*](https://arxiv.org/abs/2512.04123), v4, 4 Jun 2026; study Apr–Nov 2025.
3. Publicis Sapient, [*The Enterprise Wasn’t Built for AI*](https://www.publicissapient.com/resources/research/enterprise-ai-readiness-gap), survey of 1,550 enterprise AI decision-makers, 29 Apr–14 May 2026.
4. OpenText / Capgemini / Sogeti, [*World Quality Report 2025*](https://s23.q4cdn.com/197378439/files/doc_news/World-Quality-Report-2025-AI-adoption-surges-in-Quality-Engineering-but-enterprise-level-scaling-remains-elusive-2025.pdf), published 13 Nov 2025; 2,000+ senior executives across 22 countries and 10 sectors, quality-engineering focus.
5. Provider capabilities and limitations are referenced by EV-022–EV-028 in the [alternatives landscape](alternatives_landscape_2026-11-07.md).
