# Varda Evidence Register

**Updated:** 6 November 2026  
**Purpose:** Central register for evidence relevant to the venture thesis and opportunity hypotheses.

**Stage 1A reconciliation note (6 November 2026):** EV-010–EV-014 below are newly recorded from the primary sources cited in the referenced ChatGPT conversation. The conversation claimed that a landscape scan and EV-010–EV-014 had already been added, but those entries and `opportunity_landscape_scan_2026-11-06.md` are absent from the current `main` branch. The exact earlier rows could not be recovered; the entries below are not asserted to reproduce them. Evidence classes use the canonical labels in `AGENTS.md`. A FACT row records what a source says, not proof of customer demand.

| ID | Claim / observation | Evidence class | Source / date | Confidence | Limitations / next action |
|---|---|---|---|---|---|
| EV-001 | The company brief presents Varda as an AI operations advisory practice for e-commerce/DTC. | FACT | `source-material/original/company_brief_May_2026.html`, May 2026 | High that this was the documented historical intent | Does not validate current demand or present strategy. |
| EV-002 | The original offer comprised AI Workflow Audit and AI Readiness Assessment. | FACT | Company brief and methodology, May 2026 | High for documented offer design | No evidence of paid delivery in supplied materials. |
| EV-003 | The original methodology is Map → Score → Decide → Implement → Verify. | FACT | `source-material/original/GAP1_unified_methodology.md`, supplied 4 Nov 2026 | High for the documented method | “Implement” means preparing the client action plan in standard scope; the client performs implementation. No outcome evidence supplied. |
| EV-004 | Context Passport is designed to produce a business-specific, paste-ready AI context document. | FACT | `source-material/original/PRODUCT_context_passport_kit.md`, supplied 4 Nov 2026 | High for artifact design | Does not prove buyers value it or that it improves model output. |
| EV-005 | The market-validation document reports one close comparable after screening roughly 20 products/listings against its own filter. | FACT | `source-material/original/VARDA_market_validation.md`, supplied 4 Nov 2026 | High that the document reports this scan; low confidence in coverage/completeness | No itemized list, URLs or access dates; narrow category and filter; not demand validation. |
| EV-006 | The May company brief states 88% AI adoption and that about one-third have begun to scale. | UNKNOWN | Company brief, May 2026 | Unverified | Original survey, population, geography, definition, sample and date are not identified in the copy. Do not merge with newer or differently scoped estimates. |
| EV-007 | The proposed risk and opportunity rubrics use 1–3 scores and categorical thresholds. | FACT | Original scoring rubrics, supplied 4 Nov 2026 | High for instrument design | No calibration or predictive validity evidence supplied. |
| EV-008 | The May brief describes Varda as pre-revenue and prioritising its first paying client. | FACT | Company brief, May 2026 | High for the brief’s historical statement | Current status after May 2026 is UNKNOWN. |
| EV-009 | Businesses may struggle to translate AI access into reliable workflow outcomes. | ASSUMPTION | First-principles reset, 6 Nov 2026 | Unproven | Broad thesis; no direct customer evidence in the canonical repository. |
| EV-010 | A representative survey of 3,503 UK businesses found 32% used at least one AI technology in 2026; it also reports skills, accuracy, productivity and cost findings. | FACT | DSIT, *AI adoption survey report 2026: executive summary*, published 29 Oct 2026; fieldwork 7 Jan–21 Apr 2026; [source](https://www.gov.uk/government/publications/ai-adoption-survey-2026/ai-adoption-survey-report-2026-executive-summary) | High for the published survey results | Denominators vary by measure; skills/accuracy results are for adopters/planners, not all businesses. UK-wide results do not establish a target-segment problem, buyer, or willingness to pay. |
| EV-011 | A study of agent deployments reports reliability as a leading development challenge, human evaluation as common, and bounded execution steps in many systems. | FACT | Pan et al., *Measuring Agents in Production*, arXiv:2512.04123 v4, published 4 Jun 2026; study Apr–Nov 2025; [source](https://arxiv.org/abs/2512.04123) | High for what the paper reports; moderate for generalization | Correct sample description: 306 practitioners surveyed, filtered to 86 deployed/pilot systems, plus 20 case-study interviews. Particular figures use smaller denominators (e.g. N=60 for step count, N=31 for evaluation methods). Participation bias, geographic concentration in the Americas, and no buyer/WTP measurement. |
| EV-012 | Google Cloud, AWS and Microsoft documentation describes platform features for agent evaluation, tracing/observability, guardrails or permissions. | FACT | Vendor documentation accessed 6 Nov 2026: [Google Cloud](https://docs.cloud.google.com/gemini-enterprise-agent-platform/optimize/evaluation/agent-evaluation), [AWS](https://docs.aws.amazon.com/bedrock-agentcore/latest/devguide/observability.html), [Microsoft](https://learn.microsoft.com/en-us/azure/ai-studio/how-to/evaluate-generative-ai-app) | High that the vendors document these capabilities | Vendor-produced capability descriptions; no independent effectiveness comparison, customer sufficiency evidence, or proof of a standalone market gap. |
| EV-013 | Shopify documents Sidekick capabilities using store data/context, reusable skills and workflow generation. | FACT | Shopify Help Center, Sidekick materials accessed 6 Nov 2026: [Sidekick](https://help.shopify.com/en/manual/ai-powered-tools/sidekick), [skills](https://help.shopify.com/en/manual/ai-powered-tools/sidekick/skills), [Shopify Flow](https://help.shopify.com/en/manual/shopify-flow/create/create-workflow) | High that these capabilities are documented | Vendor claims and product documentation; scope, availability and efficacy may vary by store/plan. Does not prove Sidekick resolves all context/integration needs. |
| EV-014 | These platform capabilities make incumbent sufficiency a necessary test for H1–H3. | INFERENCE | EV-012–EV-013 and `docs/01_market/opportunity_hypotheses.md`, 6 Nov 2026 | Medium | Capability overlap warrants investigation; it does not show platforms are adequate, directly comparable to services, or preferred by target buyers. |

## Customer evidence

No customer interviews or customer-observed workflow records have been entered yet.

| Interview ID | Segment | Role | Problem discussed | Concrete example? | Consequence | Existing workaround | Buying signal | Notes location |
|---|---|---|---|---|---|---|---|---|
| — | — | — | — | — | — | — | — | — |

## Evidence entry template

- **ID:** EV-###
- **Date captured:** YYYY-MM-DD
- **Statement:**
- **Evidence class:** FACT / CUSTOMER-REPORTED / INFERENCE / ASSUMPTION / UNKNOWN
- **Source:** publisher/person/organisation, title, date, URL or interview reference
- **Scope:** geography, sample, industry, workflow, time period
- **Confidence:** high / medium / low, with rationale
- **Counter-evidence:**
- **Hypothesis affected:** H1 / H2 / H3 / H0 / H4
- **Next action:**
