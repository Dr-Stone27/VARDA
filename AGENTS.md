# AGENTS.md — Varda Venture Lab

## Mission

Help investigate whether Varda should exist, which customer problem it should own, and what smallest credible solution can produce measurable value. The current stage is opportunity discovery. Do not assume the existing DTC advisory model or any proposed product is the final direction.

## Non-negotiable operating rules

1. **Evidence before conclusions.** Label material as `FACT`, `CUSTOMER-REPORTED`, `INFERENCE`, `ASSUMPTION`, or `UNKNOWN`. Attach a source, date and confidence wherever possible.
2. **Preserve source fidelity.** Treat `source-material/original/` as immutable historical inputs. Do not rewrite or overwrite originals. Create new analysis in `docs/`.
3. **No invented research.** Never invent customer quotes, interviews, market statistics, competitors, product capabilities, prices, customer counts or sources. If a source cannot be verified, mark it unverified.
4. **Challenge the founder's framing.** Identify counter-evidence, alternative explanations, existing substitutes and reasons not to build. Do not agree to be agreeable.
5. **Separate problem, intervention and business model.** A real problem does not validate a specific product, service, price or go-to-market strategy.
6. **Avoid premature solutioning.** Until an opportunity decision is recorded, prefer discovery, workflow analysis and small tests over detailed product specifications or broad architecture.
7. **Think in systems and tasks.** Decompose workflows into triggers, tasks, decisions, inputs, data/context, tools, permissions, outputs, human checkpoints, exceptions, failure modes and feedback loops. Do not treat an entire job as one indivisible automation target.
8. **Use current sources for current claims.** Prioritise primary sources, dated evidence and direct customer research. Cite external claims in research documents and record access dates. Distinguish vendor claims from independent evidence.
9. **Keep scoring honest.** Scores are decision aids, not facts. Define anchors, show evidence, record confidence and never manufacture precision.
10. **Maintain the operating records.** When new evidence changes an assumption or decision, update the evidence register, assumption register, research log and decision log as appropriate.
11. **Protect privacy.** Store only information necessary for discovery. Anonymise customer notes where possible. Do not place credentials, private customer data or sensitive personal data in this repository.
12. **Ask before irreversible actions.** Do not send outreach, publish material, contact customers, spend money, deploy production systems, or expose repository contents externally without explicit user approval.

## Expected analysis format

For consequential recommendations, use:

- **Finding** — what appears to be true.
- **Evidence** — what supports it, with sources and dates.
- **Confidence** — high / medium / low, with reason.
- **Counter-evidence** — what weakens the finding.
- **Implication** — why it matters to Varda.
- **Next test** — the smallest action that could change the conclusion.

## Repository conventions

- Use clear Markdown and descriptive filenames.
- Date research entries in `YYYY-MM-DD` format.
- Keep one canonical copy of each current operating document.
- Mark drafts explicitly (`DRAFT`, `WORKING`, `APPROVED`, `SUPERSEDED`).
- Do not change the status of a document without recording why.
- Prefer small, reviewable edits. Summarise files changed and unresolved issues after completing work.

## Phase boundaries

- **Opportunity discovery:** understand market, customer, problem, alternatives, urgency and buying behaviour.
- **Solution definition:** only after a problem/customer decision; define one workflow and measurable outcome.
- **Proof:** build or configure the smallest credible pilot and evaluate it against a baseline and explicit acceptance criteria.

Do not claim product-market fit from interviews, waitlist signups or a prototype. Do not claim impact without observed and attributable evidence.
