# Getting Started

This guide helps you use the starter kit for a small, safe project.

## Before / After

Before:

- Scattered chat prompts
- Unclear source references
- Decisions lost in conversation history
- No review trail

After:

- Source index
- Project index
- Handoff prompt
- Human review
- Maintenance log

## Step 1: Choose a Safe Project

Start with fictional, personal, or public-safe material. Do not use private business data while learning the structure.

## Step 2: Add Project Context

Create or update rows in:

- `01_wiki/project_index.md`
- `01_wiki/source_index.md`

Keep entries short and easy to review.

## Step 3: Prepare an AI Handoff

Use `03_templates/codex_handoff_template.md` to tell an AI agent:

- What to read
- What to change
- What not to touch
- How success should be checked

## Step 4: Review the Output

AI output should be reviewed by a person before public use. Check factual claims, privacy, tone, and completeness.

## Step 5: Log the Change

Add a row to `02_routines/maintenance_log.md` for meaningful updates.

## 15-Minute Walkthrough

Use the existing fictional sample project in `04_examples/sample_project/`.

1. Spend 2 minutes reading `04_examples/sample_project/README.md` to understand the fictional scenario.
2. Spend 3 minutes reviewing `04_examples/sample_project/source_index.sample.md` and note how each source is labeled as fictional.
3. Spend 3 minutes reviewing `04_examples/sample_project/project_index.sample.md` and identify the project goal, sources, and decision notes.
4. Spend 3 minutes copying `03_templates/codex_handoff_template.md` and adapting it for one narrow task, such as drafting a fictional launch review checklist.
5. Spend 2 minutes checking the output for unsupported claims, private data, and unclear source references.
6. Spend 2 minutes adding a short entry to a maintenance log when the update is meaningful.

For practice, keep the sample project fictional. Replace real names, metrics, companies, customers, and internal links with safe placeholders before using this structure for public work.

## Korean Note

처음에는 실제 업무 자료보다 허구 예시로 연습하세요. 구조에 익숙해진 뒤에도 민감 정보는 저장소에 넣지 않는 원칙을 유지하는 것이 중요합니다.
