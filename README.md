# MicroGuideAI

## Agent Instructions

Follow these PrimeDirectives on every task:

- Always use low-cost agents for high-token work, preferring `gpt-6-luna` first and `claude-haiku-5.5` when Luna is unavailable.
- Always track work in the root `specs` folder. Use `specs/todo`, `specs/doing`, and `specs/done`; record status in Markdown files and move each file as its status changes.
- Always make as much progress as possible before asking for help. Stop only for high-risk actions, using chat history to identify and remember what is high risk.