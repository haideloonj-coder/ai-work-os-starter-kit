# Examples

These examples are fictional and public-safe. They are meant to show how the starter kit can be used without adding private data.

## Example 1: Weekly Public Market Scan

Source index entry:

```text
SRC-101 | Public Productivity Trends Article | Public article | Draft | Summarizes general interest in lightweight planning tools. | Weekly Public Market Scan | Public-safe placeholder
```

Project index entry:

```text
PRJ-101 | Weekly Public Market Scan | Draft | Example Analyst | Summarize public-safe themes from fictional or public sources. | SRC-101 | 2026-06-01
```

Handoff prompt goal:

```text
Review the source index entries for PRJ-101 and draft five public-safe market scan bullets. Mark uncertain claims clearly and do not add private company data.
```

Maintenance log result:

```text
2026-06-01 | Updated weekly public market scan notes | source_index.md; project_index.md | Added public-safe scan summary | Human review recommended
```

## Example 2: Fictional Product Launch Readiness Review

Safe fictional source summaries:

```text
SRC-201 | Fictional Beta Feedback Summary | Mock feedback | Ten fictional users asked for clearer onboarding labels.
SRC-202 | Fictional Support Checklist | Mock checklist | Launch support steps include docs, response owners, and review status.
```

Review questions:

- Are all claims supported by a source summary?
- Are metrics clearly labeled as fictional?
- Are launch risks separated from decisions?
- Has a person reviewed the final report?

Unsupported claim handling:

```text
Unsupported claim: "Users prefer the new dashboard."
Suggested note: "Needs evidence. Link to a source summary or label as a fictional assumption."
```

Human review step:

```text
Before publishing, ask a reviewer to check privacy, evidence, tone, and completeness.
```

## Example 3: Personal Learning Knowledge Base

A non-engineer can use this kit to track public articles, reusable prompts, and learning notes without storing private data.

Source tracking:

```text
SRC-301 | Public Article on Better Meeting Notes | Public article | Draft | Explains common note-taking structures. | Personal Learning Notes | No private notes included
```

Reusable prompt tracking:

```text
SKILL-301 | Summarize a Public Article | Learning workflow | Draft | Ask the AI agent to summarize key ideas, open questions, and follow-up reading.
```

Learning note:

```text
Today I learned: Public articles are easier to reuse when each note includes source title, status, summary, and next action.
```

No private data is required. Keep personal journals, confidential work notes, private links, and sensitive details out of the repository.
