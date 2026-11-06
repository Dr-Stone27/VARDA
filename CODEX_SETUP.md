# Codex setup — VARDA | Venture Lab

## 1. Prepare the workspace

1. Download and extract `VARDA_Venture_Lab.zip` to a stable folder on your computer.
2. Open the extracted `VARDA_Venture_Lab` folder in Codex (or open a terminal in that folder and start Codex there).
3. Keep the repository root open. Codex should discover the root `AGENTS.md` and the skills under `.agents/skills/`.

## 2. Verify the instructions before editing

Start a new Codex task and paste:

> Read `AGENTS.md`, `README.md`, `docs/00_foundation/first_principles_reset.md`, `docs/01_market/opportunity_hypotheses.md`, and the source register. Summarise the project's current phase, non-negotiable rules, active hypotheses, known evidence gaps and the next decision gate. Do not modify files yet. Flag any inconsistencies or unsupported claims you find.

Review the summary. Correct any misunderstanding before asking Codex to edit files.

## 3. First Codex work request

Once the setup summary is accurate, ask Codex:

> Audit the initial Varda workspace for consistency and completeness. Compare the new reset against the preserved original documents in `source-material/original/`. Do not rewrite the original files. Identify factual mismatches, missing provenance, assumptions presented as facts, duplicated or conflicting instructions, and gaps in the discovery plan. Propose specific edits with file paths, but do not apply them until I approve the change list.

This is a review task, not permission to change the venture strategy.

## 4. Use the bundled skills

The repository includes three skills:

- `market-research` — current market, technology, competitor and substitute research.
- `customer-discovery` — prospect research, discovery messages, interviews and synthesis.
- `venture-critical-review` — strategic challenge, alternatives, assumptions and decision review.

Ask Codex to use the relevant skill when the task matches. Skills are reusable workflows; `AGENTS.md` remains the durable project guidance.

## 5. Version control

The ZIP is a working folder, not a remote GitHub repository. Once extracted, you can initialise Git locally from the folder if you want version history, then connect a private remote repository of your choice. Do not publish the repository or source materials without reviewing privacy and access first.

## 6. Source-of-truth rule

The Markdown files in `docs/` are the canonical working records. `source-material/original/` is the preserved historical archive. ChatGPT is used for strategy, research and drafting; approved decisions and reusable findings must be written back into the canonical Markdown records.
