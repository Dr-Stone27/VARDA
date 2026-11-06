# AI Readiness Assessment — Process Mapping Framework
**Version 1.0 | E-Commerce / DTC Vertical**

---

## Purpose

This framework is used during the AI Readiness Assessment engagement to inventory and evaluate a company's current operational processes — before any AI tools are adopted. The goal is not to score maturity in the abstract. The goal is to identify the two or three places where AI adoption would generate the most value with the least risk, and to surface what needs to be true before that adoption can succeed.

Every output from this framework feeds directly into the Opportunity Scoring Rubric and the final deliverable.

---

## Step 1: Functional Process Inventory

Before scoring anything, map what exists. Work through each operational function with the client and document every significant repeating process.

A "significant repeating process" is any task or workflow that:
- Happens at least weekly
- Involves more than one person or system
- Produces an output that feeds into another process or a customer touchpoint
- Currently consumes meaningful time, cost, or error risk

### Functional Areas to Cover (E-Commerce / DTC)

| Function | Processes to Probe |
|----------|--------------------|
| **Product & Catalog** | New product setup, metadata entry, description writing, image processing, pricing updates, inventory updates |
| **Marketing & Content** | Campaign briefing, copy production, email sequencing, ad creative, social content, SEO content |
| **Customer Experience** | First-touch support, order inquiries, returns and refunds, review management, loyalty program management |
| **Sales & Growth** | Conversion optimization, A/B testing, personalization, upsell/cross-sell logic, affiliate management |
| **Operations & Fulfillment** | Order processing, inventory forecasting, supplier communication, returns processing, 3PL coordination |
| **Finance & Reporting** | Sales reporting, margin tracking, forecasting, reconciliation, budget tracking |
| **People & Internal Ops** | Onboarding, internal communication, knowledge management, meeting notes, project tracking |

---

### Process Inventory Template

For each process identified, capture the following:

| Field | Description |
|-------|-------------|
| **Process Name** | Short descriptive name |
| **Function** | Which area it belongs to |
| **Frequency** | How often it runs (daily / weekly / monthly / ad hoc) |
| **Owner** | Who is responsible for it |
| **Inputs** | What triggers or feeds this process |
| **Steps** | Brief description of how it works today (3–5 steps) |
| **Output** | What it produces and where that goes |
| **Team involved** | How many people touch it and in what roles |
| **Current tools** | What software is used today |
| **Time cost** | Rough estimate of hours per week/month |
| **Error rate** | How often does something go wrong |
| **Pain level** | Team's subjective rating: High / Medium / Low |

---

### Sample Completed Entry

| Field | Example |
|-------|---------|
| **Process Name** | New product description writing |
| **Function** | Product & Catalog |
| **Frequency** | Weekly (3–8 new SKUs per week) |
| **Owner** | Content coordinator |
| **Inputs** | Product spec sheet from supplier, brand voice guide |
| **Steps** | 1. Receive spec sheet. 2. Research comparable products. 3. Draft description. 4. Light edit by brand manager. 5. Upload to Shopify. |
| **Output** | Published product description on PDP |
| **Team involved** | 2 people (content coordinator + brand manager) |
| **Current tools** | Google Docs, Shopify |
| **Time cost** | ~6 hours/week |
| **Error rate** | Occasional — wrong specs used ~1x/month |
| **Pain level** | Medium |

---

## Step 2: Process Clustering

After completing the inventory, cluster processes into three categories:

### Category A — High-Volume, Rule-Based
Processes that are repetitive, follow consistent rules, have structured inputs, and produce predictable outputs. These are the strongest candidates for AI adoption.

*E-commerce examples: product description drafting, order status responses, email subject line generation, inventory reorder alerts*

### Category B — Judgment-Intensive, Data-Rich
Processes that require human judgment but are fed by large amounts of data that humans struggle to process efficiently. AI can augment — not replace — the human here.

*E-commerce examples: personalization logic, pricing decisions, demand forecasting, campaign performance analysis*

### Category C — Relationship or Context-Dependent
Processes that depend heavily on relationship, nuance, institutional knowledge, or unpredictable variation. AI adds little value here and may introduce risk.

*E-commerce examples: key account management, brand partnership negotiation, crisis communication, complex complaint resolution*

**Rule:** Only Category A and B processes are candidates for AI adoption recommendations. Category C processes should be explicitly excluded from the roadmap and the reason documented — this builds trust with the client.

---

## Step 3: Data & Infrastructure Readiness Check

For every Category A and B process identified, assess whether the underlying data and infrastructure can actually support AI adoption.

| Readiness Factor | Questions to Ask |
|-----------------|-----------------|
| **Data availability** | Does the data this process relies on exist in a structured, accessible form? |
| **Data quality** | Is that data clean, consistent, and regularly maintained? |
| **System accessibility** | Can the relevant systems be connected to an AI tool via API or integration? |
| **Volume sufficiency** | Is there enough volume to make AI adoption worthwhile? (Low-volume processes rarely justify the setup cost) |
| **Ownership clarity** | Is there a named person who owns this process and could own the AI integration? |

Score each factor: ✅ Ready / ⚠️ Needs work / ❌ Blocker

A process with two or more ❌ blockers should be removed from the priority roadmap regardless of its AI opportunity score. Flag it as a "future candidate" with a note on what needs to change first.

---

## Step 4: Risk Flagging

Before finalizing the opportunity list, apply a risk filter. For each candidate process, ask:

| Risk Type | Question |
|-----------|----------|
| **Customer exposure** | Does the AI output reach customers directly without human review? |
| **Compliance exposure** | Is this process subject to regulatory requirements (data privacy, advertising standards, consumer protection)? |
| **Revenue criticality** | If the AI gets this wrong, does it directly impact revenue (pricing errors, fulfillment failures)? |
| **Reversibility** | If the AI produces a bad output, can it be easily caught and corrected before damage occurs? |

High-risk processes are not automatically excluded — but they require a stronger governance design before adoption. Flag them clearly in the deliverable and include specific guardrail recommendations.

---

## Step 5: Output — Priority Process List

After completing Steps 1–4, produce a ranked list of processes recommended for AI adoption.

Format:

| Rank | Process | Function | Category | AI Opportunity | Data Readiness | Risk Level | Recommended First Step |
|------|---------|----------|----------|---------------|----------------|------------|----------------------|
| 1 | | | | | | | |
| 2 | | | | | | | |
| 3 | | | | | | | |

This list feeds directly into the Opportunity Scoring Rubric for detailed scoring, and into the final deliverable as the prioritized roadmap.

---

## Facilitation Notes

**How to run the process inventory with the client:**

The inventory should not be done via form alone. Run a 90-minute facilitated workshop (remote or in person) with the founder/CEO and one or two operational leads. Use a shared screen with a live document. Walk through each functional area and ask: *"Talk me through how this actually works today — not how it's supposed to work, but what actually happens."*

The gap between the official process and the actual process is often where the most significant AI opportunities hide.

**What to watch for:**

- Processes described as "it depends" — probe deeper. These often have hidden rule-based components that are automatable.
- Processes where the answer is "we just haven't documented that yet" — these are Category C risks masquerading as Category A opportunities.
- Processes where one person is named as the sole owner with no backup — high dependency risk that AI adoption will not solve and may worsen.
