# Stage 1A — Source Reconciliation

**Date:** 6 November 2026  
**Status:** Working review completed; awaiting founder approval before Stage 1B  
**Scope:** Existing Varda originals, canonical evidence/source/assumption/research/decision records, first-principles reset, and research claims already made in the referenced ChatGPT conversation. No new landscape or segment research was undertaken; that belongs to later stages.

## Finding

The reset is broadly faithful to the original Varda concept, but the source trail is incomplete and some historical claims are not independently verifiable. The current GitHub `main` branch at `422642d1b8c10ddc486e61e3d1626db59da19c36` did not contain the opportunity landscape report or the EV-010–EV-014 entries that the referenced conversation said had been added. Its exact earlier entries could not be recovered. New EV-010–EV-014 entries in the evidence register were reconstructed from the research claims visible in that conversation and verified against the identified primary sources; they are not claimed to reproduce the missing rows.

## Source reconstruction

The nine files under `source-material/original/` document a historical DTC/e-commerce AI operations advisory concept, with two proposed services (Workflow Audit and Readiness Assessment), a five-stage method, rubrics, DTC process mapping, a Context Passport, a narrow product scan, a systemic breakdown, and a commercial outreach framework. The source register now records repository paths and the provenance limitations known from the archive.

The reset correctly treats the original target segment, offers, prices and product concepts as historical rather than selected. One source-fidelity ambiguity was corrected in the reset: the original methodology's “Implement” stage produces a client action plan; it expressly excludes implementation by Varda from the standard engagement. A possible future Varda implementation offer remains a new hypothesis, not part of the original scope.

## Unsupported or weakly sourced original claims

1. **Company brief:** it states 88% AI use and one-third scaling; a $5,000–$50,000 “typical” engagement range; a two-engagement funnel; a $2M–$50M DTC target and $2M–$20M US/UK prospect band; faster contracting/buyer-behavior claims; and “validated” legal and healthcare RCM extensions priced at $15,000–$50,000. The copy does not identify the supporting surveys, geography/sample definitions, pricing observations, or independent research. These are historical claims to source or leave unverified, not current market facts.
2. **Context Passport market scan:** the document reports around 20 listings and one close comparable under its own restrictive filter. It does not provide the itemized listings, source URLs, access dates, or a reproducible search record. Its claims of a “defensible” product gap and validated $350 service tier go beyond the evidence shown. The cited Fiverr/Upwork range is attributed to “earlier research this session,” which is not preserved.
3. **Systemic breakdown:** it is labeled “Not for external use” and contains judgments about asset value, defensibility, productisation, pricing and distribution. Those judgments are internal assessments, not customer evidence. The document is in the repository; its current public/private visibility could not be confirmed in this review because GitHub's app endpoints returned 404 while authenticated Git fetch remained available. Treat visibility as UNKNOWN and review it before relying on any privacy assumption.
4. **Founder capability:** the assumption register cites “PM/systems experience” as support for delivery feasibility, but no source for that capability statement is recorded in the repository. It is now marked unverified.
5. **Historical status:** the May company brief calls Varda pre-revenue. That is a FACT about what the dated document says, not proof of current status after May 2026.

## Reconciliation of the referenced conversation's research

- **UK AI adoption survey:** the referenced conversation's figures are traceable to the UK government's 2026 survey of 3,503 businesses. The 32% figure is the share using at least one AI technology. Other reported measures have different populations/denominators; skills and accuracy concerns are reported for adopters/planners, while the survey's scope is UK businesses overall. This is useful market context, not evidence of Varda-specific pain or willingness to pay. The source and caveats are recorded as EV-010.
- **Agent reliability study:** the primary paper reports 20 case-study interviews and a survey of 306 practitioners, with 86 production/pilot systems filtered for deployed-system analysis. The conversation's phrase “86 practitioners” is inaccurate. Individual results use smaller denominators (including N=60 for steps and N=31 for evaluation methods). The paper reports reliability as a leading development challenge, but is based on a selected technical-practitioner sample, notes participation/geographic limitations, and does not study buyer demand. Recorded as EV-011.
- **Cloud platforms:** official Google Cloud, AWS and Microsoft documentation confirms some vendor-described evaluation, tracing/observability, guardrail and permission capabilities. It does not establish that the products work equally well in customers' workflows, that they are direct substitutes for a Varda service, or that they are insufficient. Recorded as EV-012.
- **Shopify:** official Sidekick documentation describes store context/data use, reusable skills and workflow generation. This establishes capabilities documented by Shopify, not their effectiveness or sufficiency for all DTC workflows. Recorded as EV-013.
- **Market implication:** platform capability overlap makes incumbent sufficiency a required test. “Formidable competitor” and “no independent opportunity” remain inferences until customer alternatives and buying behavior are examined. Recorded as EV-014.

Sources checked: [UK AI Adoption Survey 2026](https://www.gov.uk/government/publications/ai-adoption-survey-2026/ai-adoption-survey-report-2026-executive-summary); [Measuring Agents in Production](https://arxiv.org/abs/2512.04123); [Google Cloud agent evaluation](https://docs.cloud.google.com/gemini-enterprise-agent-platform/optimize/evaluation/agent-evaluation); [AWS AgentCore observability](https://docs.aws.amazon.com/bedrock-agentcore/latest/devguide/observability.html); [Microsoft Foundry evaluation](https://learn.microsoft.com/en-us/azure/ai-studio/how-to/evaluate-generative-ai-app); [Shopify Sidekick](https://help.shopify.com/en/manual/ai-powered-tools/sidekick), [Sidekick skills](https://help.shopify.com/en/manual/ai-powered-tools/sidekick/skills), and [Shopify Flow workflow generation](https://help.shopify.com/en/manual/shopify-flow/create/create-workflow). Access date: 6 November 2026.

## Repository and instruction inconsistencies

- The README still names completion of the first-principles reset as the immediate milestone; the reset and initial session agenda also describe first-stage work that has since happened.
- `chatgpt/PROJECT_INSTRUCTIONS.md` still calls completion of the reset the “First task.”
- `CODEX_SETUP.md` says the ZIP is not a remote repository, suggests setting up a private remote, and says not to publish. That conflicts with the recorded GitHub workflow. The current repository visibility should be confirmed before revising this instruction.
- The README/ChatGPT timeline places solution definition in November, while `AGENTS.md` makes it conditional on a problem/customer decision. The current founder mandate is stricter: complete Phase 1 discovery first, then wait for approval before customer discovery; do not start solution design during Phase 1.
- Compact ChatGPT copies duplicate canonical `docs/` files. They matched at the prior audit, but no sync rule prevents future drift.

## Evidence state and limits

The canonical evidence register previously contained no customer interviews, customer-observed workflow records, paying-customer evidence, deployment telemetry or independently verified case studies. No such evidence was found in the referenced conversation. The external research verified here is secondary/technical or vendor-reported evidence; it cannot establish a customer's willingness to pay. The opportunity landscape scan itself remains missing from the repository, so its full scope, sources and analysis cannot be audited.

## Stage 1A completion

**Completion conditions met:** original source claims, known provenance gaps, the repository/research handoff discrepancy, and the primary-source limitations visible in the referenced research have been recorded in the source/evidence/research registers and this report. Original files were not modified.

**Unresolved:** recovery of the missing scan and its claimed original EV-010–EV-014 rows; source URLs and methods behind historical market/price claims; current GitHub visibility/access status; current business status; and any direct customer evidence.

**Recommended next stage:** Stage 1B — market landscape, after founder approval. Do not begin Stage 1B, Stage 1C, interviews, or solution definition until approved.
