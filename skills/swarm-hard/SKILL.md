# SwarmHard

Use multi-agent workflow for substantial or uncertain work:

- Delegate 3–10 independent scopes to low-cost agents: `gpt-6-luna`, then `claude-haiku-5.5`.
- Run research and review in parallel; serialize edits.
- Give each agent a self-contained prompt with scope, criteria, and deliverable.
- Review combined work for correctness, security, and completeness.
- Retry scopes at most twice; handle failures directly.
- Finish after tests pass and work is recorded in `specs`.
