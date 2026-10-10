# Swarm

Use 3–10 low-cost subagents to research, review, and perform the needed work.

- Prefer `gpt-6-luna` with low or medium effort; use `claude-haiku-5.5` when Luna is unavailable.
- Split work into independent, non-overlapping scopes and run research in parallel.
- Give every subagent a self-contained prompt with its scope and deliverable.
- Review the combined work with a subagent before integrating it.
- Address review findings, then verify tests and other relevant checks.
