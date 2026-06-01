# Model and Tool Routing Policy

This policy helps choose the right level of AI assistance for each task.

## Routing Principles

- Use stronger reasoning for high-risk or ambiguous decisions.
- Use coding agents for repository changes, code edits, file operations, and validation.
- Use chat agents for thinking, writing, synthesis, and planning.
- Use long-context reviewers when many sources must be compared.
- Use human approval for destructive, public-facing, or sensitive changes.

## Risk Levels

| Risk level | Examples | Suggested handling |
| --- | --- | --- |
| Low | Formatting, fictional examples, template cleanup | One AI pass plus quick human review |
| Medium | Workflow changes, index restructuring, public docs | AI draft plus explicit human review |
| High | Public claims, legal/compliance content, destructive edits | Human approval before and after AI work |

## Default Behavior

When uncertain, choose the safer workflow:

1. Summarize the intended change.
2. Identify risks.
3. Ask for approval when the change is destructive or public-facing.
4. Make a focused edit.
5. Record the result in the maintenance log.
