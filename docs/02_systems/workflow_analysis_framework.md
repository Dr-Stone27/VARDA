# AI-Enabled Workflow Analysis Framework

**Version:** 0.1 — exploratory framework, not yet validated as a Varda proprietary method.

## Unit of analysis

Start with an end-to-end business outcome, then decompose it into tasks, decisions and handoffs. Do not classify an entire process as either “automatable” or “not automatable” before analysing its constituent work.

## Workflow map

For each workflow, record:

| Field | Description |
|---|---|
| Business outcome | What result is the workflow intended to produce? |
| Trigger | What event or condition starts the workflow? |
| Owner | Who is accountable for the outcome? |
| Actors | People, AI agents, applications, services or external parties involved |
| Task / decision | One bounded activity or decision in the workflow |
| Inputs | Data, documents, messages, events and instructions required |
| Source of truth | Which system or record is authoritative? |
| Context | Policies, history, definitions and organisational knowledge required |
| Tool access | Systems read or changed, including permission scope |
| Output | What is produced, changed or decided? |
| Downstream dependency | Where does the output go next? |
| Human checkpoint | Where is human judgment, approval or exception handling needed? |
| Exceptions | Known variants and edge cases |
| Failure mode | What can go wrong, how serious is it and how detectable is it? |
| Recovery | Retry, rollback, fallback, escalation or manual completion path |
| Measurement | Quality, time, cost, throughput, risk or customer outcome |

## Task treatment categories

Use these as provisional labels, not a fixed scoring system:

- **Automate:** bounded task, stable rules, suitable inputs, low or controlled consequence, verifiable output and safe recovery.
- **Augment:** AI supports a human decision or task; human remains accountable for judgment or approval.
- **Human-led:** relationship, accountability, ambiguous judgment or consequence means a person should retain primary control. AI may still assist with bounded sub-tasks.
- **Defer:** prerequisites such as data quality, permissions, process ownership or evaluation are not ready.

## Cross-cutting control questions

- What is the system authorised to read, write, send, approve or purchase?
- Are permissions least-privilege and scoped to the task?
- Which actions require explicit human approval?
- Are inputs and outputs traceable?
- How is output quality tested before deployment?
- How is behaviour monitored in production?
- How are model, prompt, data, tool and policy changes evaluated?
- What happens on timeout, tool failure, ambiguous output or conflicting instructions?
- Can actions be reversed? What cannot be reversed?
- Who owns incidents and ongoing performance?

## Evidence discipline

Do not infer accuracy from a successful demonstration. Record test-set composition, expected outcomes, edge cases, error types, human review time, cost and baseline comparison. Treat vendor benchmarks and customer-reported metrics as different evidence classes.
