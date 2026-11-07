# Stage 1E — Comparative Segment Assessment

**Date:** 7 November 2026  
**Status:** DRAFT — founder review required  
**Scope:** DTC/ecommerce, business/professional services, and software/technology only. Includes pre-adoption, current adoption and abandoned-deployment evidence where available. No segment is selected.

## Decision question and limits

This assessment compares whether public evidence makes any of the three segment groups more or less promising for workflow-level discovery. It does not establish a painful customer problem, select a customer, or establish willingness to pay. No direct customer interviews or observed workflows are in the evidence register.

The three segments do not map cleanly onto official industry classifications:

- **DTC/ecommerce:** official sources classify by economic activity, not sales channel. “Retail trade” includes online and offline retailers and is not a direct measure of DTC businesses. Eurostat's enterprise survey covers enterprises with at least 10 employees/self-employed persons in specified sectors, so its retail results do not represent many small ecommerce firms.
- **Business/professional services:** Eurostat's professional, scientific and technical activities and administrative/support activities are separate categories. The UK DSIT grouping “business services/administration” is broader and not equivalent to professional services. Sinch's professional-services category is a separate, large-enterprise industry group.
- **Software/technology:** Eurostat and DSIT “information and communication” include telecommunications, publishing, media and other activities as well as software. Sinch's “technology” group is closer to the requested segment but refers only to enterprises working on AI for customer communications.

Do not compare percentages across surveys as if they measured the same population or definition. Eurostat 2025 is the most consistent source for comparing the same official measure across economic activities. UK DSIT data adds adoption-stage context; Sinch supplies a narrow view of deployed customer-communications agents and reported rollbacks.

## Common comparison criteria

| Criterion | Evidence used consistently across segments | What it can establish | What it cannot establish |
|---|---|---|---|
| Relative adoption | Eurostat 2025 AI-use rates by activity; UK DSIT sector adoption where available | Reported use of at least one AI technology in each source's defined population | Depth, workflow criticality, deployment maturity or demand |
| Pre-adoption | Eurostat share of non-users who had considered AI; DSIT adoption status and qualitative accounts | Consideration/non-use and reported reasons or decision context | Purchase intent, near-term conversion or a problem worth solving |
| Active use | Eurostat AI purposes by activity; DSIT examples of current use and deployment approach | Reported task categories, use status and illustrative operating context | A specific workflow's quality, failure frequency, outcomes or economic impact |
| Abandoned use | Sinch reported rollback/shutdown of deployed AI customer-communications agents by industry | A bounded signal that some deployments were rolled back in the surveyed enterprise context | Broad AI abandonment prevalence, cause across all workflows, or representativeness for SMEs |
| Constraints and alternatives | Eurostat/DSIT reported barriers; existing alternatives map (`alternatives_landscape_2026-11-07.md`) | Issues respondents report and categories of available alternatives | Whether a constraint is primary, alternatives are inadequate, or buyers will pay |
| Evidence fit | Population, geography, sector mapping, sponsor, date and measure | How directly the source applies to the requested segment | Any ranking independent of the above limitations |

No numerical score or ranking is assigned. Public evidence is not a substitute for the workflow-level evidence required to distinguish H1–H3 from H0.

## Comparative snapshot

| Requested segment | Adoption: EU 2025 (Eurostat) | Pre-adoption: EU 2025 (among non-users) | UK adoption context | Active-use signal | Abandoned-deployment signal | Main fit caveat |
|---|---:|---:|---|---|---|---|
| DTC/ecommerce | Retail trade excluding motor vehicles: **15.5%** used AI | Retail trade excluding motor vehicles: **13.3%** had considered AI | In 2025, **86%** of UK retail/distribution firms neither used nor planned AI. The 2026 DSIT executive summary does not report a retail figure. | Among EU retail AI users, common purposes included marketing/sales (**48.18%**), administration (**25.84%**) and accounting/finance (**22.35%**). | Sinch reports retail customer-communications agent rollbacks, but its pages conflict: **69%** in one chapter and **71%** in another. | Retail is not DTC; small firms are underrepresented in Eurostat; Sinch is large-enterprise, customer-communications-only evidence. |
| Business/professional services | Professional/scientific/technical: **40.43%**; administrative/support: **20.0%** | Professional/scientific/technical: **24.92%**; administrative/support: **15.7%** | UK DSIT business services/administration: **23%** in its 2025 survey and **39%** in 2026. These are survey waves with different periods and must not be interpreted as a clean like-for-like sector trend without checking methodology. | EU professional/scientific/technical users reported AI purposes including business administration/management (**35.51%**) and accounting/finance (**30.87%**). | Sinch reports **85%** rollback in professional services, within its deployed/planned AI customer-communications population. | “Business services/administration,” “professional services,” and Eurostat's two separate categories are not interchangeable; survey respondents are not representative of small practices. |
| Software/technology | Information/communication: **62.52%** | Information/communication non-users: **32.05%** had considered AI | UK information/communication: **43%** in the 2025 DSIT survey and **61%** in 2026, subject to different survey waves/definitions. | EU information/communication AI users reported R&D/innovation (**42.51%**), marketing/sales (**40.64%**) and administration (**38.29%**) as purposes. | Sinch reports **66%** rollback in its technology industry group for AI customer communications. | Information/communication is broader than software; Sinch's group and workflow are narrow and enterprise-only. |

**Source notes:** Eurostat percentages are for enterprises in specified sectors and the stated denominator; the pre-adoption percentage uses only enterprises that did not use AI. Eurostat's figures measure use of at least one of its surveyed AI technologies. DSIT figures use separate UK survey instruments and sector groupings. Sinch rollback figures are reported among enterprises actively deploying/planning AI in customer communications, not all businesses in each industry. See evidence IDs EV-033–EV-035 and sources below.

## Adoption-stage evidence

### Pre-adoption

- **FACT — EU:** Among Eurostat's AI non-users in 2025, 14.21% had considered an AI technology. The corresponding shares were 32.05% for information/communication and 24.92% for professional/scientific/technical enterprises. Retail trade excluding motor vehicles was 13.3%; administrative/support was 15.7%. These are “ever considered” measures, not plans or buying intent.
- **FACT — UK:** In DSIT's 2025 survey, 80% of all surveyed businesses neither used nor planned AI; 86% of retail/distribution businesses were in that status. The report also gives current use of 43% for information/communication and 23% for business services/administration. These are descriptive status measures, not evidence that the non-users are potential customers.
- **CUSTOMER-REPORTED — UK qualitative survey accounts:** Respondents described no identified use case, unfamiliarity, limited expertise/time, or concern that automation could reduce personal service. Examples included a retail respondent valuing personal service, a retail firm planning a cheap test, and a small information/communication firm describing deployment as ad hoc. These illustrative accounts are not prevalence estimates and do not show unmet willingness to pay.
- **INFERENCE:** Pre-adoption may present a distinct discovery path around identifying a useful use case and evaluating a business case. It should not be folded into post-deployment reliability or integration problems unless a specific workflow and incident connect them.

### Active adoption

- **FACT — EU:** AI use differs materially by economic activity in Eurostat's common 2025 survey: 62.52% for information/communication, 40.43% for professional/scientific/technical, and 15.5% for retail trade excluding motor vehicles. The gap is a use-rate difference, not evidence of greater problem severity or market attractiveness.
- **FACT — EU use purposes:** Among AI-using enterprises, reported purposes vary by activity. Retail's leading listed purpose was marketing/sales; information/communication showed R&D/innovation, marketing/sales and administration; professional/scientific/technical showed business administration/management and accounting/finance. Purpose categories do not reveal workflow depth, cross-system integration, autonomy, quality or impact.
- **CUSTOMER-REPORTED — UK survey:** DSIT 2026 reports that use is concentrated in accessible, lower-complexity tools and common business areas include administration, marketing and IT. The 2025 report contains sector-specific qualitative examples and says reported deployment approaches ranged from informal trials to formal ROI analyses. The survey is broad and self-reported; it does not establish which workflow has a repeated, costly failure.
- **COUNTER-SIGNAL:** DSIT 2026 reports modest expenditure for many businesses, no expenditure in 2025 for 47% of respondents able to estimate it, no immediate financial effect for many adopters, and high/critical strategic importance for only 14%. This weakens any assumption that AI adoption automatically implies urgent paid operational support.

### Abandoned or rolled-back adoption

- **CUSTOMER-REPORTED — Sinch 2026 survey:** Sinch reports rollback/shutdown after governance failures in AI customer-communications deployments: 66% in technology and 85% in professional services. For retail, Sinch reports 69% in its “real cost” chapter and 71% in its retail article. The inconsistency is unresolved in the published pages reviewed; do not present a single retail rate as settled.
- **Population limit:** Sinch surveyed 2,527 director-, VP- or C-suite-level decision-makers at organizations with at least 1,000 employees, each responsible for AI customer-communications strategy. Organizations not deploying or planning customer-communications AI were screened out. The survey was commissioned by Sinch, a communications-platform vendor; all findings are reported practices/attitudes, not audited incidents. This is not representative evidence for SME DTC shops or business services generally.
- **Interpretive limit:** A rollback means at least one deployed customer-communications agent was stopped/rolled back after a stated governance failure. It does not mean the organization abandoned AI overall, abandoned all workflows, or remains dissatisfied after the rollback. The survey also reports high ongoing investment and continued deployment intentions, a counter-signal to permanent abandonment.
- **INFERENCE:** Rollback evidence shows that deployment and continued operation can diverge in one narrow workflow class. It raises questions about reliability, context, permissions, integration and governance, but does not identify which constraint caused each event or prove a Varda opportunity.
- **UNKNOWN:** Public evidence reviewed here does not establish segment-wide AI abandonment rates across workflows, smaller firms, or people who stopped using embedded/copilot tools. Distinguish “never adopted,” “no current use,” “not planning,” “pilot stopped,” and “production rollback” in future research.

## Shared constraints, alternatives and counter-evidence

- **FACT — EU considered non-users:** Lack of relevant expertise was the most cited reason for not proceeding (70.89%), followed by legal uncertainty (52.52%) and data protection/privacy concerns (48.83%). These results are from enterprises that had considered AI, across covered sectors; they are not sector-specific and do not establish an external-services need.
- **FACT — UK survey:** In DSIT 2025, lack of an identified use case (71%) and limited AI skills (60%) were widely reported barriers; integration/scale difficulty was reported by 29%, and data complexity by 21%. The question and denominator differ for current users and non-users. These general barriers cannot be assigned to any one requested segment from the aggregate figures.
- **COUNTER-EVIDENCE — incumbent sufficiency:** EV-022–EV-030 documents platform-native, specialist, workflow/iPaaS, enterprise-search and services alternatives. The availability of these products does not prove sufficiency, but means discovery should ask what customers already use and why it does or does not work.
- **COUNTER-EVIDENCE — no-use rationale:** DSIT reports many firms see no relevant use or have no plans. That can mean opportunity has not been identified, but it can also mean AI is not useful or worthwhile for their work. Do not treat non-adoption itself as demand.

## Segment-level discovery gaps (not a shortlist)

These are questions the comparative evidence leaves open; they do not rank segments or recommend a customer/workflow.

| Segment | What needs direct investigation | Distinguishing evidence to seek |
|---|---|---|
| DTC/ecommerce | Whether any issue is concentrated in DTC operators rather than retail generally; firm size and platform mix; seasonality; whether customer-facing AI is used, stopped or avoided; who owns customer and operational workflows. | Recent examples tied to order/service, product/catalog, merchandising, inventory or marketing workflows; exact systems and handoffs; what was stopped versus never adopted; consequence, workaround, volume and existing spend. |
| Business/professional services | Which service types and firm sizes are hidden by broad categories; whether internal productivity use differs from client-facing delivery; confidentiality/client obligations and responsibility for output. | A recent workflow from input through review and delivery; examples of adoption or rejection; rework/client impact; who sets quality/permissions and pays for tools or staff. |
| Software/technology | Whether “information/communication” statistics apply to software firms; whether technical teams' AI workflows differ from internal business use; whether engineering organizations have capacity to resolve issues themselves. | Specific development, support, sales or internal operations workflow; incident and rollback history; integration/context/reliability boundary; time allocated to workaround and actual alternatives. |

Across all groups, test H1, H2, H3 and H0 using the incident-level distinctions in `hypothesis_assessment_2026-11-07.md`. Include pre-adoption, active-use and stopped-use cases; do not sample only visible adopters. Ask for recent behavior and artifacts where appropriate, not hypothetical product interest. Do not infer willingness to pay from survey participation or expressed concern.

## Assessment and stage gate

**Finding:** The same-source EU evidence indicates higher AI use and consideration among information/communication and professional/scientific/technical enterprises than in retail. UK evidence broadly points in the same direction for its own categories. A narrow vendor-commissioned survey reports substantial rollback in large-enterprise AI customer communications across retail, technology and professional services, but cannot support a general segment ranking and has conflicting retail figures.

**Confidence:** Medium for the direction of relative sector-level adoption within Eurostat's covered EU enterprise population; low for translating it to Varda's actual segment groups; low for prevalence/meaning of rollback outside the Sinch survey's defined large-enterprise workflow population. No evidence here establishes customer urgency, root cause, unmet need or WTP.

**What could reverse the interpretation:** DTC-specific evidence may differ sharply from general retail; smaller professional services and software companies may have little AI use or no budget; high adoption may reflect adequate bundled tools and internal engineering; observed rollbacks may be detected-and-managed incidents rather than ongoing unmet needs; non-adoption may reflect rational low value.

**Stage 1E completion conditions:**

1. All three specified segments were compared using the same criteria without adding segments or selecting a winner.
2. Pre-adoption, active adoption and abandoned/rolled-back use were addressed, with unavailable and conflicting evidence explicitly marked.
3. Sources, population, sector mapping, sponsor and limitations are recorded; customer evidence is not implied.
4. The evidence register and research log are updated.

**Status:** Conditions are met for founder review. Remaining public-source gaps are explicit and cannot be resolved by further aggregate market statistics alone.

**Recommended next stage:** Stage 1F, after founder approval: use the three-group comparison to recommend the strongest candidate customer/workflow combinations for primary research, explain remaining unknowns, and nominate interview roles. This recommendation should be a discovery shortlist only, not a segment or hypothesis selection. No customer outreach has been sent.

## Sources reviewed 7 November 2026

1. Eurostat, [*Use of artificial intelligence in enterprises*](https://ec.europa.eu/eurostat/statistics-explained/SEPDF/cache/106920.pdf?v=1383188104890435), 2025 ICT survey data (data extracted Dec 2025; report version available June 2026). Sector rates, purposes, consideration and reasons for non-use.
2. UK DSIT, [*AI adoption survey report 2026: executive summary*](https://www.gov.uk/government/publications/ai-adoption-survey-2026/ai-adoption-survey-report-2026-executive-summary), published 29 Oct 2026; survey fieldwork 7 Jan–21 Apr 2026, n=3,503; plus 50 follow-up interviews and 7 site visits. Broad sector rates, adoption stage, impact and barriers.
3. UK DSIT, [*AI Adoption Research* (2025 survey, web version)](https://www.gov.uk/government/publications/ai-adoption-research/ai-adoption-research), published 28 Jan 2026, updated 13 Feb 2026; n=3,500, weighted for business size/sector, 9% response rate, with 100 qualitative follow-up interviews. Sector adoption status, non-adoption, use and illustrative respondent accounts.
4. Sinch, [*About “The AI Production Paradox” research: Methodology*](https://sinch.com/ai-production-paradox/chapter/research-methodology/), Jan 2026 fieldwork; n=2,527 across 10 countries and 6 industries; 1,000+ employees; screened for current/planned customer-communications AI; commissioned by Sinch.
5. Sinch, [*AI Customer Communications in Production: The Real Story*](https://sinch.com/ai-production-paradox/chapter/ai-production-challenges/), industry rollback data.
6. Sinch, [*The Real Impact of AI Failures in Customer Communications*](https://sinch.com/ai-production-paradox/chapter/real-cost-failures/) and [*AI in Retail Customer Communications*](https://sinch.com/blog/ai-retail-customer-communications/), retail-specific rollback data. These pages conflict on the retail rollback rate (69% vs 71%); unresolved.
7. Varda, [`alternatives_landscape_2026-11-07.md`](alternatives_landscape_2026-11-07.md) and [`hypothesis_assessment_2026-11-07.md`](hypothesis_assessment_2026-11-07.md), for substitute capability boundaries and hypothesis-level counter-evidence.
