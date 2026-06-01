# Codex Handoff Template

Copy and adapt this prompt when asking a coding agent to work in the repository.

```text
You are working inside this repository only.

Task:
[Describe the specific task.]

Context to read first:
- README.md
- 00_system/update_rules.md
- [Relevant index or template]

Boundaries:
- Do not use private data.
- Keep examples fictional.
- Prefer additive updates.
- Explain risky or destructive changes before applying.

Success criteria:
- [Expected files or outputs]
- [Validation method]
- [Maintenance log update if needed]
```

## Example A: Weekly Public Source Index Update

```text
You are working inside this repository only.

Task:
Update the public-safe source index for a weekly review.

Context to read first:
- README.md
- 00_system/update_rules.md
- 01_wiki/source_index.md

Boundaries:
- Do not use private data.
- Keep all examples fictional or public-safe.
- Do not add API keys, OAuth tokens, internal file paths, private notes, or real company metrics.
- Prefer additive updates.

Steps:
- Review the current source index structure.
- Add short fictional/public-safe source summaries.
- Mark uncertain or placeholder items clearly.
- Update 02_routines/maintenance_log.md with the change.
- Validate that no private data was added.

Success criteria:
- 01_wiki/source_index.md has clear, safe entries.
- 02_routines/maintenance_log.md records the update.
- All source summaries are fictional or public-safe.
```

## Example B: Fictional Launch Report Review

```text
You are working inside this repository only.

Task:
Review the fictional sample launch report materials and prepare a short review checklist.

Context to read first:
- README.md
- 00_system/update_rules.md
- 04_examples/sample_project/README.md
- 04_examples/sample_project/project_index.sample.md
- 04_examples/sample_project/source_index.sample.md
- 03_templates/report_brief_template.md

Boundaries:
- Keep all sample data fictional.
- Do not add real company names, private metrics, customer data, internal paths, or confidential notes.
- Mark unsupported claims instead of presenting them as facts.
- Prefer a concise checklist over a long report.

Steps:
- Read the sample project files and report brief template.
- Draft a short review checklist for the fictional launch report.
- Identify any claims that need evidence or clearer labeling.
- Confirm that the sample remains fictional and public-safe.

Success criteria:
- The checklist is copy-paste friendly for a non-engineer.
- Unsupported claims are clearly marked.
- No private or real company data is introduced.
```
