---
name: add-or-update-skill
description: Workflow command scaffold for add-or-update-skill in everything-claude-code.
allowed_tools: ["Bash", "Read", "Write", "Grep", "Glob"]
---

# /add-or-update-skill

Use this workflow when working on **add-or-update-skill** in `everything-claude-code`.

## Goal

Adds a new skill or updates an existing skill, including documentation and configuration.

## Common Files

- `skills/*/SKILL.md`
- `docs/zh-CN/skills/*/SKILL.md`
- `docs/tr/skills/*/SKILL.md`

## Suggested Sequence

1. Understand the current state and failure mode before editing.
2. Make the smallest coherent change that satisfies the workflow goal.
3. Run the most relevant verification for touched files.
4. Summarize what changed and what still needs review.

## Typical Commit Signals

- Create or update SKILL.md in the appropriate skills/ directory
- Optionally update related documentation or integration files

## Notes

- Treat this as a scaffold, not a hard-coded script.
- Update the command if the workflow evolves materially.