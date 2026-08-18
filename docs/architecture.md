# Architecture

## Lifecycle

`capture -> classify -> preserve -> derive when needed -> curate -> review`

1. Capture unclassified information in `inbox/`.
2. Copy an external source into `raw/` without changing its content or name.
3. Create a `derived/` artifact only when a readable, searchable, or structured representation is needed.
4. Create concise, source-aware knowledge pages in `wiki/`.
5. Link pages through `wiki/index.md`, record successful maintenance in `wiki/log.md`, and review the vault with a read-only lint.

## Knowledge maturity

- `source fact`: directly supported by a traceable source.
- `understanding`: an explanatory restatement by the vault author.
- `inference`: a conclusion that requires validation.
- `open question`: an unresolved item with a next action.

Do not promote an inference to a stable knowledge page without recording the evidence or validation that supports it.

## Wiki categories

The numbered folders are an intentionally small default, not a fixed taxonomy. Rename, add, or remove categories only through a documented structural change.

- `00-home`: navigation and orientation.
- `01-concepts`: stable definitions and relationships.
- `02-methods`: reusable procedures and techniques.
- `03-source-notes`: notes tied to specific sources.
- `04-projects`: active project knowledge.
- `05-experiments`: reproducible runs, observations, and outcomes.
- `06-learning-notes`: provisional learning material.
- `07-questions`: unresolved questions and next actions.
- `08-writing`: synthesis, reports, and publication drafts.
