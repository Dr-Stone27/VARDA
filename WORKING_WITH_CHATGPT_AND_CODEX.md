# Working across ChatGPT and Codex

## Responsibilities

| Environment | Owns | Does not own |
|---|---|---|
| ChatGPT Project | Venture reasoning, research synthesis, customer discovery design, strategic choices and coaching | Unreviewed edits to the repository or unilateral changes to approved decisions |
| Codex workspace | Repository inspection, documentation changes, architecture, code, prototypes, tests and technical execution | Quietly redefining the venture thesis or treating an unapproved proposal as a decision |
| `docs/` Markdown records | Canonical state of the venture: thesis, hypotheses, evidence, assumptions, decisions and plans | Raw chat history or unsupported claims |

## The sync loop

1. Explore a question in the ChatGPT Project.
2. Separate what is known from inference and assumptions.
3. Agree whether the finding is a proposal or an approved decision.
4. Update the relevant canonical Markdown file in the repository (with Codex or directly).
5. Ask ChatGPT to work from the updated record, not from a remembered draft.
6. If new evidence changes a decision, update the evidence register, assumption register and decision log.

## One source of truth

The repository is canonical for current venture facts and decisions. A ChatGPT conversation can propose a change, but the change becomes part of the working system only when captured in the relevant document and approved by the founder.

## Chat naming convention

Use one ChatGPT Project with separate chats for distinct outcomes:

- `00 | Founder OS and operating decisions`
- `01 | First-principles reset`
- `02 | Market and technology intelligence`
- `03 | Customer discovery and outreach`
- `04 | Opportunity selection`
- `05 | Product and technical definition`
- `06 | December pilot and proof`

## Avoid context drift

- Do not maintain a separate competing copy of a key document in ChatGPT and Codex.
- When sharing a new decision with either environment, include the decision-log entry or update the canonical file first.
- Mark working hypotheses as hypotheses until evidence supports a change in status.
- Keep historical source documents intact.
