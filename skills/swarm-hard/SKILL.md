# SwarmHard

Use a disciplined multi-agent workflow for substantial or uncertain work:

- Delegate 3–10 independent scopes to low-cost agents, preferring `gpt-6-luna`, then `claude-haiku-5.5`.
- Run research and read-only review in parallel; serialize edits to avoid conflicting changes.
- Give each agent a self-contained prompt, exact scope, acceptance criteria, and deliverable.
- Require a final review of the combined work for correctness, security, and completeness.
- Turn valid findings into focused follow-up work, retrying a scope at most twice before handling it directly.
- Finish only after relevant tests or checks pass and the work is recorded in `specs`.
