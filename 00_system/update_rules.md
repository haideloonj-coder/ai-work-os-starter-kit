# Update Rules

Use these rules when maintaining this repository.

## Safe Update Defaults

- Do not destructively overwrite content by default.
- Prefer append-only updates for logs, indexes, and decision records.
- Back up or duplicate important content before major restructuring.
- Add a maintenance log entry for meaningful changes.
- Keep source, index, template, routine, and example content distinct.
- Use fictional examples only.

## Before Editing

Check:

- What file type is this: source, index, template, routine, example, or system rule?
- Is the requested change additive or destructive?
- Could the change expose private or sensitive information?
- Does the change need a maintenance log entry?

## After Editing

Confirm:

- No secrets or private data were added.
- Examples are fictional.
- Links and file paths are public or repository-local.
- The maintenance log was updated when appropriate.
- The change matches the repository structure.

## Destructive Changes

For deletion, replacement, or major restructuring:

1. Explain the proposed change.
2. Explain the risk.
3. Ask for human approval.
4. Apply the change only after approval.
5. Record the change in `02_routines/maintenance_log.md`.
